# RS232-Infrared-Optical-Meter-Reading-Head
How to solve the challenges of meter data acquisition using DLMS & EDMI protocols?
I. Project Background: Obstacles encountered in collecting data from special protocol electricity meters?
Project Basic Information
• Project Location: South Korea
• Project Type: Factory Energy Consumption Data Collection
This project is implemented by Shanghai Data Acquisition IoT Technology Co., Ltd. (official website: daq-iot.com).
Core challenge: How to achieve efficient data collection from EDMI meters?
Given the unique data acquisition requirements of the EDMI protocol meter (Mk6E), how can real-time data monitoring be achieved without disassembling the meter or modifying the wiring?
<img width="569" height="719" alt="图片1" src="https://github.com/user-attachments/assets/ea94cdb5-4560-4d73-931b-b3ee2cd98d5d" />

Project implementation difficulties
• Meter restrictions: Disassembling and rewiring the meter on site is prohibited.
• Interface limitations: Only optical communication ports (infrared communication) are retained.
• Unique protocol: Unconventional State Grid protocol, making parsing difficult.
• Clear requirements: low cost, simple cabling, wireless transmission
II. Technical Solution:
Scheme Composition
• Hardware device : DAQ-IOT Optical Port Reader(DAQ-GP-NIRUSB)
• Software support: General data acquisition software (DAQ FOR IIOT)

Technological advantages
• Protocol Adaptation: Successfully overcame the challenge of reading and parsing the EDMI protocol.
• Easy installation: No disassembly required, only connection to the optical communication port.
• Remote management: Supports remote debugging and configuration
• Data integration: MQTT + JSON standard format, compatible with customer platforms.
III. On-site Implementation: How to complete the deployment quickly?
Implementation process







1.Infrared probe fixed installation
2. The data acquisition equipment is powered on-site.
3. Remote technical debugging and configuration
4. Data integration with customer platforms
Data transmission standards
• Transport protocol: MQTT
• Data format: JSON custom fields
IV. Implementation Results: What were the data collection outcomes?
Core data collection
• Total positive active power
• Positive active peak/flat/valley power
• Total reverse active power and time-of-use power
• Total positive reactive power and time-of-use power

Project Value
✅ Successfully implemented EDMI protocol for infrared data acquisition from electricity meters
✅ No need to disassemble and rewire, minimizing on-site modifications
✅ 4G wireless transmission, low cost and easy deployment
✅ Real-time data monitoring ensures efficient operation of photovoltaic power plants
