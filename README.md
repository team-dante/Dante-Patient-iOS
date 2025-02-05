# Dante Patient
Dante Patient is a medical mobile app designated to improve patient visit experience. As the primary audience in the medical fields are patients, patient care experience is an ongoing and noble goal. However, due to intense workloads, staff may oftentimes leave out how well do patients feel about their visits. Therefore, Dante Patient opens up a solution for enhancing patient visit experience and service quality by providing the following features:

- Real-time location tracking of physicians inside the radiation oncology clinic
- Auto timer (no button press) to track the time a patient spent at each treatment stage
- Collect all the time data and draw statistical conclusion via tables and/or graphs
- Survey page (voluntarily) for patients to give feedback to staff to improve service

## Getting Started
1. Open the terminal, go to the directory where you would like to store this project.
2. Type `git clone https://github.com/team-dante/Dante-Patient-Swift.git`
3. Navigate to project folder `cd Dante-Patient-Swift`
4. Then, open `Dante Patient.xcworkspace`; hit play at the top-left corner of Xcode

## Screen Archetypes
* Login
    * Allows patients to use their own phone numbers and PINs assigned by the oncology clinic staff. 
* Activate Account / Sign Up
    * Allows first-time patients to enter their phone numbers to activate their accounts (assigned by staff beforehand). 
* Radiation Oncology Clinic Map
    * Allows patients to view their positions in the waiting list.
    * Allows paitents to track physicians' location inside the oncology clinic in real-time.
* Time Tracker
    * Allows patients to see how much time they have spent at treament rooms. For instance, when a patient enters a room, he/she will have his/her own qr code ready to scan in. Once they scan in, the clock will start automatically.
    * Reset clock to 0 sec when a patient is out of the current treatment room.
* Stats
    * Allows patients to see the time spent at each treatment stage in visual-appealing graphs. They may choose the time span of a day, month, or year
    * Allows patients to see the visit flow of a paritcular day
* Profile Screen
    * Allows patients to log out
    * Allows patients to use their own qr codes for scanning into rooms
    * Allows patients to add their own qr codes to Apple Wallet for easy access
    * Allows patients to provide for feedback for the clinic services anytime (voluntarily)

## Documentation
Please visit our [documentation](https://team-dante.github.io/dante-patient-docs/) website for a detailed walkthrough of the app.

*Documentation will be updated soon.*

## Future Development
- 3D image rendering to illustrate patients' treatment progress

## Contributors

- [Hung Phan](https://github.com/hp0101)
- [Xinhao Liang](https://github.com/xinhao128)

## Lisense

	Copyright 2019 Hung Phan and Xinhao Liang

	Redistribution and use in source and binary forms, with or 
	without modification, are permitted provided that the following 
	conditions are met:

	1. Redistributions of source code must retain the above copyright 
	notice, this list of conditions and the following disclaimer.

	2. Redistributions in binary form must reproduce the above copyright 
	notice, this list of conditions and the following disclaimer in the 
	documentation and/or other materials provided with the distribution.

	3. Neither the name of the copyright holder nor the names of its 
	contributors may be used to endorse or promote products derived from 
	this software without specific prior written permission.

	THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS 
	"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT 
	LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR 
	A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT 
	HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, 
	SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED 
	TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR 
	PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF 
	LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING 
	NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS 
	SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
