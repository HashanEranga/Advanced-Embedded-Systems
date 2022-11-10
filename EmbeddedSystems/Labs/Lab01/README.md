# Accessing Mbed Simulator
Windows and Mac users: Downloading and Running Mbed Simulator image files with Docker Desktop To download the Mbed Simulator image files in a Windows or Mac OS, follow these steps: 
1. Ensure that you have successfully installed Docker Desktop as described in Downloading and
installing Docker Desktop.
2. Open a terminal command prompt and run the following command to download the
necessary Mbed Simulator image files: 
```
docker pull armedu/mbed_sim
```
3. Run the Mbed Simulator by entering the following command:
```
docker run -p 7829:7829 armedu/mbed_sim
```
4. Expand your OS system tray (or status bar, depending on your OS), and right click on the Docker Icon. Then select Dashboard

5. Hover your mouse over the relevant container named ‘mbed_sim’ and select ‘Open in Browser’.