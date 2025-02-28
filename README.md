# MATLAB-Graph-Plotter

This project is a MATLAB-based application built with App Designer that allows users to construct and visualize circles based on specific geometric rules. The application facilitates interactive user input via mouse clicks and dynamically displays geometric elements with the following features:

    User Interaction & GUI Design:
    A robust graphical user interface enables users to input points directly by clicking on the canvas, with options to hide or reveal various geometric elements for clarity.

    Circle Construction:
        First Circle: Constructed by letting the user specify a center and a point on its circumference.
        Second Circle: Automatically drawn tangentially to the first circle by computing the appropriate radius based on user input.
        Third Circle: Developed through a more advanced procedure where the application "snaps" user-input points to the nearest circle, computes perpendicular bisectors, and determines the circle's center and radius via intersection of bisectors.

    Advanced Geometric Features:
    The project includes functionality to calculate intersections between circles and to perform geometric transformations. By translating and rotating the constructed elements using homogeneous coordinates, the application aligns the figures with the axes seamlessly.

    File Handling & Novel Extensions:
    Users can save and replay point input sessions through file operations, while additional novel features extend the base functionality—enhancing interactivity and offering further visual insights into the geometric constructions.
