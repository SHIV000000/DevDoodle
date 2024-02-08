# DevDoodle Blog

## Table of Contents
- [Description](#description)
- [Key Features](#key-features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Description

The DevDoodle Blog is a web application designed for developers and tech enthusiasts to share, explore, and engage in tech-related content. With a focus on simplicity and visual appeal, this blog provides an intuitive platform for users to create, edit, and discover posts without the need for authentication. Dive into the world of technology, express your thoughts, and connect with like-minded individuals through the DevDoodle Blog.

## Key Features

1. **Simplified User Experience:**
   - No authentication required for seamless access.
   - Intuitive and user-friendly design.

2. **Visually Appealing Interface:**
   - Elegant post cards with shadows and hover effects.
   - Captivating header styling with a unique font and color scheme.
   - Thoughtfully selected typography for readability.

3. **Clean and Uncluttered Layout:**
   - Ample whitespace for a clean and organized appearance.
   - Adjusted margins and paddings for improved spacing between elements.

4. **Tech-Centric Content:**
   - Users can create, edit, and explore tech-related posts.
   - Dynamic post index for easy navigation.

5. **Responsive Design:**
   - Ensures a seamless experience across various devices.

## Installation
To run the DevDoodle Blog locally, follow these steps:

###  Clone the Repository

```bash
git clone https://github.com/SHIV000000/DevDoodle.git
```
```bash
cd WorkWave
```
**Create a Virtual Environment**

**On macOS/Linux:**
   ```bash

   python3 -m venv venv
   ```
**Activate the Virtual Environment:**
```bash
source venv/bin/activate
 ```
**On Windows:**
```bash
py -m venv venv
```

**Activate the Virtual Environment:**
```bash
.\venv\Scripts\activate
```

## Install Dependencies:

```bash
pip install django
```
**Apply Migrations:**

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```
**Create Superuser (Optional)**

 ```bash
python manage.py createsuperuser
```
**Run the Development Server**

```bash
python manage.py runserver
```

Visit http://127.0.0.1:8000/ in your browser.
