# Xiaozhi AI
##  Preparation Before Use  
Step 1. Switch the ICRobot internal firmware to Xiaozhi AI, the method can refer to the [Mode Switching](https://icreate-help-center.yuque.com/dxifg8/mddwgb/fn2d0706ggrnqizu)。

**Step 2:** Complete the Xiaozhi AI configuration for ICRobot. For detailed configuration instructions, refer to [Xiaozhi AI Setup Guide](https://icreate-help-center.yuque.com/dxifg8/mddwgb/npqvx527t7ghwhfe)。

 The Xiaozhi AI function can be used only after all of the above steps have been completed.  

##  Available Functions  
###  Voice Control and Recognition  
####  Definition  
ICRobot integrates a front-facing noise-canceling microphone array and combines local and cloud-based speech recognition engines to accurately recognize Mandarin and various dialect commands. Users can control basic robot functions, such as starting, stopping, turning, and adjusting the speed, using voice commands. The system also supports a customizable command vocabulary, enabling flexible expansion for different projects.  

####  Command Description  
| Command Type | Example Commands |
| :---: | :---: |
| Motion Control | (Robot) move forward/backward (… seconds/cm) |
| | (Robot) turn left/right (… seconds/degrees) |
| Peripheral Control | Port (1/2/3/4) robotic gripper (open/close) |
| | Port (1/2/3/4) launcher fire (… bullets) |
| Line Tracking | Start auto line tracking<br/>Stop auto line tracking |
| Sound Control | Set current volume to (0–100) |


Notes:

Motion Commands: Avoid using “keep moving (forward/backward/left/right)” commands, as continuous movement may cause recognition errors and be difficult to stop. If this command is used, you can press the middle button to stop movement.

Line Tracking: When controlling line tracking by voice, press the middle power button to stop tracking.

#### Usage Steps:
1. Switch the robot to XiaoZhi AI mode (skip this step if already switched).
2. Power on ICRobot.
3. Give a voice command, e.g., “Hello XiaoZhi, move forward for 5 seconds.”

Note: After startup, the system defaults to single-dialogue mode. To switch between single and continuous dialogue modes, say: **“Switch to (continuous/single) dialogue mode.”**

### Intelligent Voice Interaction
#### Definition
In AI interaction mode, ICRobot supports natural speech-based dialogue, allowing users to ask questions or control devices through conversational commands.

#### Command Guide
| Category | Example Commands |
| :---: | :---: |
| Device Status | Check current device status (battery level / charging status / Wi-Fi strength / volume level) |
| Vision | See what’s in front |
| Free Q&A | Ask about weather, time, culture, geography, music, etc. |


#### Usage Steps:
1. Switch the robot to XiaoZhi AI mode (skip if already switched).
2. Power on ICRobot.
3. Say “Hello XiaoZhi” to activate the dialogue and start Q&A interaction.

Note: The system starts in single-dialogue mode by default. To toggle between single and continuous dialogue modes, say: **“Switch to (continuous/single) dialogue mode.”**
