# Project Overview #
This project is a C++ based encryption and decryption tool using AES-128 and OpenCV for both images and text. It implements two modes of operation for encryption:

AES-128 ECB (Electronic Codebook Mode)
AES-128 CBC (Cipher Block Chaining Mode)
The tool ensures secure handling of sensitive data by applying robust cryptographic methods.

# Features #
**Google Maps Integration:**
Displays user locations and overlays interactive red zones indicating areas of potential exposure.
Maps patient traces with precise distance measurements to nearby users.

**Dynamic Red Circles:**
A 10m radius red circle represents the personal exposure zone of a user who may have been in contact with a COVID-19 patient.
A 100m radius red circle indicates a high-risk red zone where confirmed cases have been reported.

**Proximity Alert System:**
Tracks user movement in real-time.
Alerts the user with a notification if they enter a red zone (100m radius) or come within close proximity (10m radius) to a high-risk individual.

**Distance Measurement:**
Computes the distance between the user's current location and the red zones or nearby patient traces.
Visualized directly on the map to ensure transparency and informed decision-making.

**User-Friendly Visualization:**
Intuitive Google Maps interface that dynamically updates as users move.
Red zones and proximity alerts provide a clear indication of risk areas.
