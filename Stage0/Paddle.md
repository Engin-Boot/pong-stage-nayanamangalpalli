# Paddle

## Features

Handling Paddle Movements

### Scenario: Identification of key pressed

Given - Each user has one paddle
And: handles paddle movements using up and down keys

When - When user presses a either up or down key

Then - Identifies pressed key

### Scenario: Paddle Movements

Given - Presses either up or down key

When - Pressed Key is identified

Then - Based on key pressed, a y coordinates of paddle are either increased or decreased.

### Scenario: Collison Detection

Given -  Each user has one paddle.
And: one ball for all users

When - a ball hits a paddle

Then - bounce a ball
