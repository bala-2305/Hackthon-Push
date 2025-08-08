# Hackthon-Push-Disease-Detection-Image

Disease detection model with image detection


#Reasons

**This is a basic app that uses efficiency net-0b.pth model for predictions and display the graph based output for image predictions 

**I am using the plant village dataset from kaggle.com which has about 15 classes which is a basic crop and also it will display the detection as multiple classes so its easy for the farmer to  understand the disease stats......

["Pepper__bell___Bacterial_spot",
"Pepper__bell___healthy",
"Potato___Early_blight",
"Potato___Late_blight",
"Potato___healthy",
"Tomato_Bacterial_spot",
"Tomato_Early_blight",
"Tomato_Late_blight",
"Tomato_Leaf_Mold",
"Tomato_Septoria_leaf_spot",
"Tomato_Spider_mites_Two_spotted_spider_mite",
"Tomato__Target_Spot",
"Tomato__Tomato_YellowLeaf__Curl_Virus",
"Tomato__Tomato_mosaic_virus",
"Tomato_healthy"]

multi lingual collection::

LANGUAGES = {
    "English": {
        "title": "🌿 Plant Disease Identifier",
        "upload": "Upload a plant leaf image",
        "predict": "Predict Disease",
        "result": "Predicted Disease:",
        "copy_label": "Predicted Disease (you can copy):",
        "page_select": "Select Page"
    },
    "தமிழ்": {
        "title": "🌿 தாவர நோய் அடையாளம் காண்பவர்",
        "upload": "தாவர இலை படத்தையெற்றவும்",
        "predict": "நோயையை கணிக்கவும்",
        "result": "கணிக்கபட நோய்:",
        "copy_label": "கணிக்கபட நோய் (நகலெறுக்கலாம்):",
        "page_select": "பக்கத்தைத் தேர்ந்தெடுக்கவும்"
    },
    "हिन्दी": {
        "title": "🌿 पौधों के रोग पहचानें",
        "upload": "पौधे की पत्ती की छवि अपलोड करें",
        "predict": "रोग की भविष्यावानी करें",
        "result": "अनुमानित रोग:",
        "copy_label": "अनुमानित रोग (कापी कर सकते हैं):",
        "page_select": "पृष्ठ चुनें"
    }
}

# --------- TRANSLATIONS ---------
TRANSLATIONS = {
    "Pepper__bell___Bacterial_spot": {"தமிழ்": "மிளகு___பாக்டீரியா புள்ளி", "हिन्दी": "मिर्च___बैक्टीरियल स्पॉट"},
    "Pepper__bell___healthy": {"தமிழ்": "மிளகு___ஆரோக்கியம்", "हिन्दी": "मिर्च___स्वस्थ"},
    "Potato___Early_blight": {"தமிழ்": "உருளைக்கிழங்கு___ஆரம்பம் நிறம்", "हिन्दी": "आलू___अर्ली ब्लाइट"},
    "Potato___Late_blight": {"தமிழ்": "உருளைக்கிழங்கு___தாமத நிறம்", "हिन्दी": "आलू___लेट ब्लाइट"},
    "Potato___healthy": {"தமிழ்": "உருளைக்கிழங்கு___ஆரோக்கியம்", "हिन्दी": "आलू___स्वस्थ"},
    "Tomato_Bacterial_spot": {"தமிழ்": "தக்காளி___பாக்டீரியா புள்ளி", "हिन्दी": "टमाटर___बैक्टीरियल स्पॉट"},
    "Tomato_Early_blight": {"தமிழ்": "தக்காளி___ஆரம்ப நிறம்", "हिन्दी": "टमाटर___अर्ली ब्लाइट"},
    "Tomato_Late_blight": {"தமிழ்": "தக்காளி___தாமத நிறம்", "हिन्दी": "टमाटर___लेट ब्लाइट"},
    "Tomato_Leaf_Mold": {"தமிழ்": "தக்காளி___இலை பூஞ்சை", "हिन्दी": "टमाटर___लीफ मोल्ड"},
    "Tomato_Septoria_leaf_spot": {"தமிழ்": "தக்காளி___செப்டோரியா இலை புள்ளி", "हिन्दी": "टमाटर___सेप्टोरिया लीफ स्पॉट"},
    "Tomato_Spider_mites_Two_spotted_spider_mite": {"தமிழ்": "தக்காளி___இரண்டு புள்ளி சில்லி பூச்சி", "हिन्दी": "टमाटर___स्पाइडर माइट्स"},
    "Tomato__Target_Spot": {"தமிழ்": "தக்காளி___இலக்கு புள்ளி", "हिन्दी": "टमाटर___टारगेट स्पॉट"},
    "Tomato__Tomato_YellowLeaf__Curl_Virus": {"தமிழ்": "தக்காளி___மஞ்சள் இலை சுருக்கம் வைரஸ்", "हिन्दी": "टमाटर___पीलापन पत्ता कर्ल वायरस"},
    "Tomato__Tomato_mosaic_virus": {"தமிழ்": "தக்காளி___மொசாயிக் வைரஸ்", "हिन्दी": "टमाटर___मोज़ेक वायरस"},
    "Tomato_healthy": {"தமிழ்": "தக்காளி___ஆரோக்கியம்", "हिन्दी": "टमाटर___स्वस्थ"}
}
