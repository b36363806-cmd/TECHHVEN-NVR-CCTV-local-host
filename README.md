pkg update -y && pkg upgrade -y
pkg install python ffmpeg -y
pip install flask requests
termux-setup-storage


cd ~/storage/downloads/TECHHVEN_NVR_CCTV

chmod +x start.sh
./start.sh
