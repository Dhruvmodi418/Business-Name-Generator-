# Business-Name-Generator-
Only Frontend Business Name Generator

Business Name Generator
A lightweight, front-end project that programmatically generates three-word business names using randomized logic.

Key Features
Dynamic Logic: Uses Math.random() to select from different word sets for each part of the business name.

Three-Tier Generation: Combines an adjective, a business descriptor, and a corporate suffix to create a complete name.

Randomization Ranges: Implements specific probability thresholds (0–0.33, 0.33–0.66, and 0.66–1.0) to ensure a balanced distribution of results.

Template Literals: Uses modern ES6 string interpolation to log the final name to the console.

How it Works
First Word: Randomly selects between "Crazy", "Amazing", or "Fire".

Second Word: Randomly selects between "Dhruv", "Foods", or "Garments".

Third Word: Randomly selects between "Bros", "Limited", or "Hub".

Output: Concatenates the choices and displays them via console.log().
