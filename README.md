# Recipe Finder

## Overview
AI Recipe Finder is a web-based application developed using Django and Machine Learning. The system allows users to upload an image of a food item and receive recipe recommendations along with nutritional information, ingredients, cooking time, and preparation steps.
The application uses image-based food recognition and matches detected food items with a recipe dataset to provide relevant cooking suggestions.

## Features
- Upload food images
- Food recognition using Machine Learning
- Recipe recommendation system
- Display ingredients and cooking instructions
- Show cooking time and calorie information
- User-friendly web interface
- Django-based backend

## Technologies Used
### Frontend
- HTML5
- CSS3

### Backend
- Python
- Django

### Libraries
- Pillow (PIL)
- NumPy
- JSON
- Base64

### Database
- SQLite3

## How It Works
1. User uploads a food image.
2. Image is processed by the recognition model.
3. Detected food labels are generated.
4. Recipes are matched from the dataset.
5. The system displays:
   - Recipe Name
   - Ingredients
   - Cooking Time
   - Calories
   - Preparation Directions

## Run the Project
Start server:
python manage.py runserver
Open: http://127.0.0.1:8000

## Dataset
The project uses:
- Food image encodings
- Recipe dataset stored in JSON format
- Nutritional information
- Ingredient lists
- Cooking instructions

## Future Enhancements
- User authentication
- Save favorite recipes
- Advanced nutrition analysis
- Mobile responsive design
- Deep learning food classification
- Multi-language support

## Team Members
This project was developed by a team of 3 members.
### Team
- Bhumika M
- H R Vidya
- Lisha S

## Learning Outcomes
- Django Web Development
- Machine Learning Integration
- Image Processing
- Dataset Management
- MVC Architecture
- Python Development