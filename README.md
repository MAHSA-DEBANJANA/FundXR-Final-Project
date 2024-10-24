# Virtual Science Fair
## Extended Reality Mini Project

## Team Members
- Mahsa NIAZI
- Debanjana HALDAR

## Project Overview
This VR application creates an immersive educational environment simulating a science fair with interactive physics and chemistry exhibits. Users can explore different rooms and interact with scientific demonstrations using a PICO VR headset.

## Project Files
We have uploaded our files in this link as GitHub doesnt allow for uploading files above 25 MB via upload
- Google drive Folder:
  https://drive.google.com/drive/folders/1jPFQzVoNQffeWP5LZVEVIjwEzL_TUGUo?usp=drive_link
- APK File (33.6 MB):
  https://drive.google.com/file/d/1kLhFemr6DCa7gSE4z_qPkMKtMKsh7DGE/view?usp=drive_link
- Project ZIP File:
  https://drive.google.com/file/d/1thStlZVQhJDT_J5FvF4R8k53o2l-L6af/view?usp=sharing

## Implementation Details

### Environment Structure
- Main entrance with an interactive door
- Two separate exhibition rooms
  - Room 1: Physics Exhibit (Solar System and Gravity Demonstration)
  - Room 2: Chemistry Exhibit (Volcanic Reaction Demonstration)

## Room 1: Physics Exhibit
### Features
- Interactive Solar System display
- Gravity comparison demonstration table
- Components:
    - Main display table
    - Secondary table with reset button
    - Two interactive balls for gravity testing
    - Designated testing zones for different gravitational fields
### Interactions
- Ray-casting selection for objects
- Object manipulation through ray-casting
- Comparative gravity zones
- Physics-based interactions for gravity demonstration
- Reset functionality (applied but non-functional)

## Room 2: Chemistry Exhibit
### Features
- Interactive volcanic reaction demonstration
- Components:
    - Miniature volcano model
    - Two interactive bottles:
        - Soda bottle
        - Vinegar bottle
    - Chemical reaction visualization
### Interactions
- Implementation of touchpad-based gliding/flying movement
- Door mechanism at entrance
- Grabbable bottles
- Ray-casting for distant object interaction
- Interactive pouring mechanism
- Chemical reaction trigger system (applied but non-functional)
- Reset functionality (applied but non-functional)

## Technical Implementation
### Working Features
- Ray-casting interaction system
- Basic physics implementation
- Object grabbing mechanics
- Door interaction mechanism
- Basic scene navigation

### Known Issues
1. Reset Functionality:
    - Reset buttons in both rooms are non-functional
    - Scene state persistence issues
    - Canvas and TextMeshPro components not rendering properly in VR space
2. Timer System:
    - Implementation attempted but non-functional
    - Integration issues with main scene
    - Canvas and TextMeshPro components not rendering properly in VR space
3. Volcano reaction System
    - Implementation attempted but non-functional

## Technical Challenges
1. Hardware Setup:
    - Difficulties with PICO headset configuration
    - Limited development time due to hardware setup issues
    - Computer compatibility challenges
2. UI Implementation:
    - Canvas and TextMeshPro integration issues in VR space
    - Problems with text rendering and scaling in 3D environment
    - Difficulties in maintaining consistent UI visibility across different viewing angles
3. Development Constraints:
    - Reduced tutorial and development time due to hardware setup issues and limited experience
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
  🗸 Virtual navigation via touch pad   
  🗸 Ray casting Manipulation   
  🗸 Object activation/deactivation  
  🗸 Physics implementation  
  🗸 Lighting implementation  
  🗸 3D audio integrated in the scene  
  𐄂 Canvas + 3D TextMeshPro  
      - Timer functionality (applied but non-functional)  
      - Reset functionality (applied but non-functional)  
  🗸 Interactive object behaviors  

## Scripts 
In Project documentation File: [github.com/MAHSA-DEBANJANA/FundXR-Final-Project/blob/main/Documentation.pdf](https://github.com/MAHSA-DEBANJANA/FundXR-Final-Project/blob/main/Documentation.pdf)

## Conclusion
While the project successfully implements core VR interactions and educational demonstrations, technical challenges and time constraints impacted the full implementation of all planned features. The foundation for an engaging educational VR experience has been established, with clear paths for future improvements and optimizations.
