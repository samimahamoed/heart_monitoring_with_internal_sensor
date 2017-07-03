# heart_monitoring_with_internal_sensor

The project implementation was intended to investigate the use of inertial sensors to measure heart rate and heart rate irregularity by placing the sensor at various points, while controlling body posture. The implemented software process the sampled acceleration data to extract the pulse waveform and identify the location of the peaks in the pulse signal. Then the time difference between the peaks will be transmitted through Bluetooth link to the host iOS application, which will be collecting similar data from all similar devices in the vicinity.
