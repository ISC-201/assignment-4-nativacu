# Assignment-4
- [ ] If you haven't already please create a release for version **v0.0.3**. It should represent your work for *Assignment 3*.
- [ ] Add code logic to render the representation of a thruster for every time your ship is moving forward (should disappear when not going forward).
- [ ] If you haven't already add to your math utilities class a function to convert angles to radians.
- [ ] If you haven't already add to your math utilities class a function to convert radians to angles.
- [ ] If you haven't already add to your math utilities class a public static member that representes PI.
- [ ] In class, we've talked about affine transformations and how points/vectors are transformed using matrices. [Read](https://www.khronos.org/registry/OpenGL-Refpages/gl2.1/xhtml/glRotate.xml) about the function `glRotate` and get ready to use it to make our ship rotate.
  - [ ] Implement the Player's `RotateLeft` function. Similar to moving forward constant increments should be added to an internal variable that represents orientation.
  - [ ] Implement the Player's `RotateRight` function. Similar to moving forward constant increments should be added to an internal variable that represents orientation.
  - [ ] Use your internal variable representation of orientation to transform the ship's orientation.
  - [ ] Your ship should move to were its pointing rather than move vertically on a constant path across the screen.
- [ ] Add a **mass** member to your `Player` class.
- [ ] Re-factor our render function implementation. Use STL containers to handle the ship's points and the thruster's points. 
- [ ] Create a new `Asteroid` class. Internally it should be similar to our `Player` class.
  - [ ] Asteroids can be SMALL, MEDIUM & BIG. Add the proper code to represent this.
  - [ ] Define an `Update` function, meant for updating the Asteroid simulation.
  - [ ] Define and implement a `Render` function, which should render a static asteroid on the center of the screen. Experiment with point variations and other techniques to achieve a proper Asteroid shape. Remember asteroid size should affect the render size.
  - [ ] Define and implement a `GetSize` function, should return the Asteroid size.
- [ ] Modify your code in a way code repetition is minimal.

## Notes
* Your code repo should be referenced as a sub-module for this assignment.
