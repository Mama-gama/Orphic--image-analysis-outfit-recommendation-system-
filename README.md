# Orphic--image-analysis-outfit-recommendation-system-

- **Purpose**: The Orphic app 🤖 is designed to analyze skin tone and body shape to provide personalized fashion recommendations.
  
- **Skin Tone Analysis**: Users can upload images, which are analyzed using computer vision techniques to classify skin tones as fair, dusky, or dark. This is based on color range thresholds in LAB color space, calculating the percentage of each tone in the image 📸.

- **Body Shape Analysis**: Users input measurements such as bust, waist, hips, and gender. The app then calculates ratios between these measurements to identify body shapes like hourglass, pear, or rectangle.

- **Personalized Suggestions**: Based on the analyzed data, the app generates tailored fashion suggestions for the user. These recommendations include detailed descriptions and images representing clothing styles and accessories that complement the user's specific skin tone and body shape classification 💻.

- **Implementation**: Developed using Flask, a Python web framework, the Orphic app comprises multiple routes for different functionalities such as skin tone analysis, body shape analysis, and suggestion generation. It also offers intuitive navigation through various HTML templates.

- **Empowerment**: The Orphic app aims to empower users by providing them with personalized fashion insights, enabling them to make informed decisions about clothing styles and accessories that best suit their unique characteristics 🔍.
