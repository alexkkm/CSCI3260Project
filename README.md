# CSCI 3260 Project

	- Name: KONG Kwai Man
	- Student ID: 1155125979

	- Name: NG Yu Chun Thomas
	- Student ID: 1155157839


Project setup:
1. In Visual Studio, open project properties setting, in linker/general add the dependencies/freeglut;dependencies/glew;dependencies/glm; into additional libraries.
2. In linker input, add opengl32.lib;freeflut.lib; glew32.lib; into other dependencies.
Run the source.cpp to see the outcome


Project Specification:

Keyboard interaction to adjust the light source:
	1st light source:
		q,w		increase/decrease diffuse reflection coefficient for 1st light source
		z,x		increase/decrease specular reflection coefficient for 1st light source
		a,s		increase/decrease ambient reflection coefficient for 1st light source
	2nd light source:
		o,p		increase/decrease diffuse reflection coefficient for 2nd light source
		n,m		increase/decrease specular reflection coefficient for 2nd light source
		k,l		increase/decrease ambient reflection coefficient for 2nd light source

Keyboard controll for the movement of space craft:
	left	move the space craft to the left
	right	move the space craft to the right
	up		move the space craft to the up
	down	move the space craft to the down

Mouse Movement: Change of the view angle

Interaction added for bonus point:
	When the space craft is moved close to the 3 UFOs (no more than 7.0f distnace for any 1 UFOs), both the target UFO and space craft will turn grey to indicate they are crashing with each others.
	When the space craft is near the rocks and the Earth, the space craft will become invinceble.
	Both interaction effect will be removed after the condition is not fulfill any more when the status updated.

