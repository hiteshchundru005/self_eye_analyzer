Eye Sight Detection System - README
Overview
This web application uses computer vision and machine learning to analyze eye health and vision quality through a standard webcam. It provides assessments for visual acuity, refractive errors, astigmatism, pupil response, eye alignment, and other key eye health metrics.

Features
Real-time eye tracking with face landmark detection

Visual acuity estimation (simulated Snellen chart)

Refractive error measurement (myopia/hyperopia)

Astigmatism detection

Pupil response analysis

Eye alignment assessment

Detailed eye measurements (pupil size, iris size, gaze direction)

Personalized recommendations

Technologies Used
TensorFlow.js - Machine learning framework

Face Landmarks Detection Model - For facial feature tracking

HTML5 Canvas - For real-time visualizations

MediaDevices API - For camera access

How to Use
Grant camera permissions when prompted

Position yourself 30-50cm from the camera in good lighting

Click "Start Camera" to begin the eye tracking

Click "Capture Eyes" to take a snapshot for analysis

Click "Analyze" to process the eye image

View results in the categorized tabs:

Vision (acuity, refraction, astigmatism)

Eye Health (pupil response, alignment, red reflex)

Details (pupil size, iris size, gaze direction)

System Requirements
Modern browser with WebGL support (Chrome, Firefox, Edge)

Webcam with at least 720p resolution

Stable internet connection (for loading TensorFlow models)

Limitations
Results are estimates only, not medical diagnoses

Accuracy depends on lighting conditions and camera quality

Requires proper positioning and cooperation from user

Does not replace professional eye examinations

Future Enhancements
Integration with actual visual acuity tests

More accurate refractive error calculations

Additional eye health assessments (glaucoma risk, cataracts)

User accounts for tracking progress over time

Mobile app version with optimized camera controls

Disclaimer
This application is for informational purposes only and is not intended to replace professional medical advice, diagnosis, or treatment. Always seek the advice of your eye care professional with any questions you may have regarding your vision or eye health.
