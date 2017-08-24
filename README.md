# android-bluetooth-zxing-barcode-scanning

This Android App is designed to be installed on VR glasses and used in warehourse to improve efficiency.

Its bluetooth part gets location info from a controller and continuously scan barcode or QR code. After the Zxing extract message from scanned code, message will be send back to controller and controller will verify whether this is the target package to be picked up. We will get controller feedback by bluetooth again.

The project is modified based on https://github.com/journeyapps/zxing-android-embedded by adding bluetooth part, changing activity content and modifing front end design.
