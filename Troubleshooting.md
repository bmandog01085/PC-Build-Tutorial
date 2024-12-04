# Troubleshooting

## 1. PC Won't Power On
Possible Causes:
- Loose Connections: A cable might not be fully plugged in.
- Faulty Power Supply: The PSU may not be providing power.
- Motherboard Short: Incorrect standoff placement could cause a short circuit.

Solutions:
1. Ensure the PSU switch is turned on and the power cable is securely connected to the outlet.
2. Verify all power connections:
- 24-pin motherboard power cable.
- 8-pin CPU power cable.
- GPU power cables (if applicable).
3. Check that the front panel power button is correctly connected to the motherboard.
4. Remove and reinstall the motherboard to ensure no standoff or metal contact is shorting it.

## 2. No Display on Monitor
Possible Causes:
- Monitor Issues: Monitor or cable might be faulty.
- GPU/Integrated Graphics: GPU may not be seated properly, or the monitor is connected to the wrong port.

Solutions:
1. Ensure the monitor is powered on and set to the correct input source.
2. Double-check the connection between the monitor and the PC:
- Use a known working cable (e.g., HDMI, DisplayPort).
- Try a different monitor if available.
3. If using a dedicated GPU, connect the monitor to the GPU’s output, not the motherboard.
4. Reseat the GPU in its slot and ensure it’s powered.

## 3. Fans Spin, but No Boot (No POST)
Possible Causes:
- RAM Issues: RAM sticks may not be installed correctly.
- CPU Issues: Improper installation or thermal paste application.
- BIOS Configuration: Outdated or incompatible BIOS.

Solutions:
1. Reseat the RAM:
- Remove and reinstall each RAM stick.
- If multiple sticks are installed, test with one stick at a time in different slots.
2. Recheck the CPU:
- Ensure it’s properly seated in the socket.
- Verify the cooler is correctly mounted.
3. Reset the BIOS:
- Remove the CMOS battery for 5-10 minutes and reinstall it.
4. Update the BIOS if the CPU is incompatible with the current version.

## 4. Overheating or Loud Fan Noise
Possible Causes:
- Cooling Issues: Thermal paste may be misapplied, or fans may not be working correctly.
- Dust Build-Up: Excess dust can block airflow.
- Poor Airflow: Improper cable management or fan placement.

Solutions:
1. Check that all fans are spinning and correctly connected to the motherboard or PSU.
2. Reapply thermal paste if necessary (ensure an even, thin layer).
3. Clean out any dust using compressed air.
4. Adjust case fan placement to improve airflow:
- Front/bottom fans: Intake.
- Top/rear fans: Exhaust.

## 5. Storage Device Not Detected
Possible Causes:
- Loose or Incorrect Cables: SATA or M.2 connections may be loose.
- BIOS Settings: Drive may be disabled in BIOS.

Solutions:
1. Recheck connections:
- For SATA drives, ensure both the data cable (to motherboard) and power cable (from PSU) are securely connected.
- For M.2 SSDs, ensure it’s screwed into place.
2. Enter the BIOS and check if the drive is recognized.
- Enable the drive if it’s disabled.
3. If using an older OS, confirm it supports modern drives (e.g., NVMe).

## 6. Random Restarts or Crashes
Possible Causes:
- Power Issues: PSU may not provide enough wattage.
- Driver Problems: Outdated or incorrect drivers.
- Thermal Throttling: Overheating can cause shutdowns.

Solutions:
1. Check that your PSU meets the power requirements of your components.
2. Update all drivers (GPU, motherboard chipset, etc.).
3. Monitor system temperatures using tools like HWMonitor.
- If overheating, improve cooling as described above.

## 7. Peripherals Not Working
Possible Causes:
- USB Ports: May be disabled or faulty.
- Driver Issues: Missing drivers for specific devices.

Solutions:
1. Test peripherals in different USB ports (front and back panel).
2. Reinstall drivers for the affected device.
3. Check BIOS settings to ensure USB ports are enabled.

## 8. Internet Not Working
Possible Causes:
- Network Drivers: May not be installed.
- Cable or Wi-Fi Issues: Faulty cables or misconfigured Wi-Fi.

Solutions:
1. Install network drivers from the motherboard’s support page.
2. Verify the Ethernet cable is connected or that the Wi-Fi antenna is attached.
3. Test connectivity with another device to rule out ISP issues.

## 9. No Sound
Possible Causes:
- Incorrect Output Device: The wrong speaker/headphone output is selected.
- Driver Issues: Missing or outdated audio drivers.

Solutions:
1. Check sound settings and ensure the correct output device is selected.
2. Update audio drivers from the motherboard or sound card manufacturer.
3. Test with a different speaker or headphone.

## 10. General Troubleshooting Tips
- Check Your Manual: Refer to the motherboard, PSU, and case manuals for guidance.
- Google the Error Codes: If you see any error codes or beep sequences during boot, look them up in the motherboard manual or online.
- Ask for Help: Online forums like Tom’s Hardware or Reddit’s r/buildapc can provide support.

[Back to Start](Introduction.md)

[Previous Page](Assembly.md)
