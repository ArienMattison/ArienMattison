- 👋 Hi, I’m @ArienMattison
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ArienMattison/ArienMattison is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
sudo mkdir /etc/X11/xorg.conf.d
sudo apt-get install xinput-calibrator
sudo xinput_calibrator
Section "InputClass"
    Identifier "calibration"
    MatchProduct "LBPS/2 Fujitsu Lifebook TouchScreen"
    Option "Calibration" "224 4021 177 3971"
    Option "SwapAxes" "0"
    EndSection
    sudo nano /etc/X11/xorg.conf.d/99-calibration.conf
    
