# Virtual Science Fair - Project Documentation
## Extended Reality Mini Project
### Université Paris-Saclay - October 2024

## Project Overview
This VR application creates an immersive educational environment simulating a science fair with interactive physics and chemistry exhibits. Users can explore different rooms and interact with scientific demonstrations using a PICO VR headset.

## Implementation Details

### Environment Structure
- Main entrance with an interactive door
- Two separate exhibition rooms
  - Room 1: Physics Exhibit (Solar System and Gravity Demonstration)
  - Room 2: Chemistry Exhibit (Volcanic Reaction Demonstration)

### Room 1: Physics Exhibit
#### Features
- Interactive Solar System display
- Gravity comparison demonstration table
- Components:
  - Main display table
  - Secondary table with reset button
  - Two interactive balls for gravity testing
  - Designated testing zones for different gravitational fields

#### Interactions
- Ray-casting selection for objects
- Grabbable balls for gravity testing
- Comparative gravity zones (applied but non-functional)
- Reset functionality (applied but non-functional)

### Room 2: Chemistry Exhibit
#### Features
- Interactive volcanic reaction demonstration
- Components:
  - Miniature volcano model
  - Two interactive bottles:
    - Soda bottle
    - Vinegar bottle
  - Chemical reaction visualization

#### Interactions
- Grabbable bottles
- Interactive pouring mechanism
- Chemical reaction trigger system
- Reset functionality (applied but non-functional)

### Core Mechanics
1. Navigation:
   - Implementation of touchpad-based gliding/flying movement
   - Ray-casting for distant object interaction
   - Direct grab mechanics for close objects

2. Interaction Systems:
   - Door mechanism at entrance
   - Object manipulation through ray-casting
   - Physics-based interactions for gravity demonstration
   - Chemical reaction trigger system
   - Timer (applied but non-functional)

### Technical Implementation
#### Working Features
- Ray-casting interaction system
- Basic physics implementation
- Object grabbing mechanics
- Door interaction mechanism
- Basic scene navigation

#### Known Issues
1. Reset Functionality:
   - Reset buttons in both rooms are non-functional
   - Scene state persistence issues

2. Timer System:
   - Implementation attempted but non-functional
   - Integration issues with main scene

## Technical Challenges
1. Hardware Setup:
   - Difficulties with PICO headset configuration
   - Limited development time due to hardware setup issues
   - Computer compatibility challenges

2. Development Constraints:
   - Reduced tutorial and development time due to hardware setup issues
   - Integration challenges with VR input systems

## Future Improvements
1. Bug Fixes:
   - Implement working reset functionality
   - Fix timer system implementation
   - Optimize performance for smoother VR experience

2. Feature Enhancements:
   - Add additional interactive elements
   - Improve visual feedback for interactions
   - Enhance physics simulation accuracy

## Project Requirements Checklist
✅ Virtual navigation via touchpad  
✅ Ray-casting manipulation  
✅ Object activation/deactivation  
✅ Physics implementation  
❌ Timer functionality (applied but non-functional)

❌ Reset functionality (applied but non-functional) 
✅ Interactive object behaviors  

## Conclusion
While the project successfully implements core VR interactions and educational demonstrations, technical challenges and time constraints impacted the full implementation of all planned features. The foundation for an engaging educational VR experience has been established, with clear paths for future improvements and optimizations.
