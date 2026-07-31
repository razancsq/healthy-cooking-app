# HealthyCooking

HealthyCooking is a mobile application for discovering recipes, planning meals, and tracking nutrition. It helps users maintain a balanced diet by combining personalized recommendations with practical meal planning tools.

## Overview

Maintaining a healthy diet is difficult when recipes and meal plans are not tailored to individual needs, time, or preferences. HealthyCooking addresses this by letting users search recipes by cuisine, meal type, or preparation time, exclude unwanted ingredients, and receive smart suggestions based on what they already have at home. The app also provides meal planning and nutrition tracking tools so users can build structured, balanced meal plans and follow their progress over time.

## Features

- Recipe discovery with filters for cuisine, dietary restrictions, preparation time, and more
- Personalized recipe recommendations based on user preferences and goals
- Smart ingredient substitutions when items are missing
- Weekly meal planner with full control to adjust generated plans
- Integration with nutritional databases to calculate calories and macronutrients
- Recipe and community sharing with comments and ratings
- User profile management with dietary goals, allergies, and preferences
- Analytics dashboard with visual reports on nutrition and progress

## System Architecture

The system follows a three-layer architecture:

1. Presentation Layer: handles all user interaction. Built with SwiftUI for iOS and XML-based layouts for Android.
2. Application / Logic Layer: handles authentication, profile management, recipes, and meal planning. Built with Swift for iOS and Kotlin for Android.
3. Database Layer: responsible for storing, retrieving, updating, and deleting system data securely, using a SQL-based database.

## Platforms

HealthyCooking is designed as a native mobile application for iOS and Android.

## Documentation

Full project documentation is available in the `docs/` folder:

- `Project_Proposal.docx` / `Project_Proposal.pdf`: project proposal and objectives
- `SRS.pdf`: software requirements specification
- `SDS.pdf`: software design specification
- `SPMP.pdf`: software project management plan
- `STP.pdf`: software test plan
- `HealthyCooking_Project_Report.docx` / `HealthyCooking_Project_Report.pdf`: summary report covering the project as a whole
