# Procedural Standardization

This checklist is designed to ensure the procedural standardization of VR studies. Below are the standardized instructions for designing and documenting all aspects of the study, including descriptions of the simulation, hardware, environmental, participant interactions, measurements, as well as ethical, accessibility, and safety considerations. Adhering to these protocols allows other researchers to replicate the study accurately, minimizing discrepancies across different settings.

---

## Reporting of VR Procedures

### VR Simulation

- Provide a comprehensive description of the simulation used, including its name, version number, and any plug-ins or extensions.
- If a custom simulation was developed, provide the source code or clear instructions for accessing the data repository (see protocols for data repositories).
- Document the length of each trial or task, including any breaks or pauses in the experiment. Extended periods in VR can contribute to both cognitive fatigue and cybersickness, so this information is crucial for replicability.
- Document the simulation mode (e.g., content streaming via link mode or deployment directly on headset) and researcher involvement during the experiment (e.g., manipulating the environment during runtime).
- Describe the observatory condition during the experiment (e.g., people present in the room during experiment or the observation of participants via camera or screencast)

### Hardware

- Document the make and model of the head-mounted display, specifying its resolution, field of view, and refresh rate.
- If applicable, describe the controllers used, including details on their interaction mode.
- If applicable, describe the motion-tracking system used (e.g., base stations, body markers, motion-tracking gloves).
- If applicable, list key hardware specifications of the computer running the VR simulation, particularly the GPU, as it impacts performance and simulation fidelity.
- If applicable, list how participants listened to any accompanying audio (e.g., whether headphones are noise canceling or not; audio level used).

### Physical Space

- Provide a detailed description of the room or space used for the study, including dimensions and any relevant physical objects (e.g., furniture or obstacles) that could interact with the VR simulation.

### Participant Instructions

- Provide a detailed description of the instructions presented to participants, such as how they engaged with the VR simulation, whether any training or familiarization periods were in place (including their duration), if there were any movement constraints, and when the instructions were communicated (i.e., prior or during simulation).
- Provide a detailed description of the tasks to be performed by participants in the VR simulation (e.g., interacting with confederates, observing a chain of events).
- Provide a detailed description of the instructions given and tasks performed within the lab while outside of the VR simulation.

---

## Standard Battery of Measurements

Researchers have measured a wide range of variables that are unique to VR simulations. While it is not feasible to account for every potential confounding factor, VR researchers commonly agree that presence should always be measured as a baseline in any VR study. Presence is a crucial indicator of participants' sense of being within the virtual environment, making it a foundational metric for assessing employees’ experience with the VR simulation. In addition, the experience of VR may differ among new and veteran VR users–due to a diminished novelty effect. Given their significance, standardized measurements of presence and VR familiarity allow for consistent comparisons across studies.

Researchers are also encouraged to include additional measurements depending on the specific aims and scope of their VR study. These additional metrics can provide further insights into participants’ experiences and the underlying mechanisms of VR interactions, ultimately enhancing the study’s robustness and replicability.

As with all research, researchers should adhere to transparent reporting protocols and include references for their chosen measurement scales, a codebook, and a scoring protocol.

### Baseline

- Include a measurement of presence (i.e., the feeling of being physically present in the virtually enriched world). Can include self, social, and telepresence.
- Include a measurement of VR familiarity (i.e., the prior exposure participants have had to VR technology).

### Additional VR-Specific Measurements

If locomotion is induced:
- Include a measurement of cybersickness (i.e., an experience of nausea, disorientation, and/or oculomotor-issues while using VR).

If participants have a virtual body:
- Include a measurement of body ownership (i.e., the feeling that the virtual body belongs to oneself).
- Include a measurement of agency (i.e., the feeling that the virtual body accurately follows the movements of one’s own movements).

If virtual humanoids are present:
- Include a measurement of social presence (i.e., the feeling of being physically present with another humanoid entity in the virtually enriched world).
- Include a measurement of the uncanny valley effect (i.e., the discomfort evoked by interacting with virtual humans or robots that are almost realistic).

If participants interact with virtual objects:
- Include a measurement of usability (i.e., the perceived ease of use of interacting with digital assets)

---

## Ethics

This checklist is designed to ensure that VR studies are conducted ethically, with careful consideration of participants’ autonomy, mental well-being, and data privacy. Each point addresses core ethical concerns specific to VR simulations, emphasizing transparency, respect for participants’ rights, and minimizing psychological harm–enhancing the opportunity for replication studies.

### Informed Consent

- Ensure participants understand the immersive nature of an VR simulation, including the heightened physical (e.g., cybersickness) and psychological (e.g., emotional distress) impacts that might arise. Provide participants with the ability to withdraw at any time without penalty.
- Allow participants to make informed decisions about how their data is collected, stored, and shared, with particular attention to sensitive data like biometric or interaction data.

### Data Privacy and Security

- Ensure that all data collection, handling, and storage comply with relevant privacy regulations (e.g., HIPAA, GDPR) to protect participants' personal information.
- Implement robust encryption protocols for all sensitive VR-related data, including biometric, spatial, and interaction data, both in transit and at rest. This ensures that participant data remains secure, even in the event of a data breach or unauthorized access. Use end-to-end encryption when transferring data to external servers or collaborating institutions.
- Be explicit about the type of data being collected and the ways in which it will be used, including the potential for long-term storage or reuse of the data in future studies.

### Managing Emotional Distress

- Acquire ethical approval from a relevant Institutional Review Board (IRB) or equivalent ethics committee.
- Evaluate the potential for VR simulations to create intense emotional responses due to heightened immersion (e.g., participants might feel more "present" in experiences such as harassment, discrimination, or accidents, which could result in more significant distress than in traditional media).
- Inform participants about the immersive nature of VR and the potential for heightened emotional reactions. Specify any potentially distressing scenarios in the consent forms.
- Ensure measures are in place to mitigate any lasting psychological harm.
- Include mandatory debriefing sessions post-experiment, especially when simulations involve sensitive content that could cause distress.
- Provide on-site mental health support, such as access to a counselor or psychologist, for participants who experience emotional distress during or after the VR simulation. Ensure participants are aware of this support option beforehand.
- Unless the research question requires otherwise and consent has been acquired, ensure that both the physical and virtual environments respect personal space, avoiding (virtual) humans from invading the participants’ proximity.

---

## Accessibility

This checklist is designed to ensure that VR studies are conducted inclusively, with careful consideration of accessibility for all participants, including those with disabilities. This further builds upon the ethicality of the study design, with each point addressing core accessibility concerns specific to VR simulations. Implementing these practices not only enhances the inclusivity of the study but also improves the replicability of the research by allowing a larger pool of participants and ensuring easier approval from ethics boards.

### Inclusive Design

- Design for the average participant: Unless the research question focuses on a specific subpopulation, develop an VR simulation that does not exclude large groups of people (e.g., people without VR and/or gaming experience).
- Design beyond the average participant: Unless the demands of the research question require otherwise, develop an inclusive VR simulation that addresses the needs of as many potential participants.
- Supplement visual cues with audio cues, icons, or filters to support participants who are colorblind. Avoid relying solely on color for conveying important information.
- Allow participants to adjust the size and distance of objects for better visibility and interaction, particularly for participants with vision impairments.
- Enable participants to choose their dominant hand within the simulation to accommodate participants who are left-handed.
- Provide options for hand-tracking or controller-based interactions for participants with limited mobility. If movement within the VR environment is necessary, offer alternatives for seated experiences.
- Include subtitles or closed captions for hearing-impaired participants, while acknowledging that subtitles may induce cybersickness in some cases. Therefore, ensure that this feature can be toggled on or off as needed.
- Select participants equitably, without bias related to race, gender, socioeconomic status, or access to VR technology–unless the demands of the research question require otherwise.

### Simplified Design

- Limit the number of buttons or complex input sequences to make the simulation accessible to participants with limited dexterity and/or gaming experience.
- Highlight interactable objects and provide visual cues to steer people towards the virtual elements that are important for the study.
- Limit the number of tasks or interactions participants need to manage simultaneously to reduce cognitive load. Break down tasks into smaller steps and offer clear guidance for each part.

---

## Safety

This checklist is designed to ensure that VR studies are conducted safely, with careful consideration of participant well-being and cybersickness. Each point addresses core safety concerns specific to VR simulations, including hardware and laboratory setup considerations, to create a safe research environment–enhancing the opportunity for replication studies.

### Hardware & Laboratory Setup

- Use headsets with 90Hz refresh rates or higher and 6DoF (Six Degrees of Freedom) tracking to reduce latency and improve the user experience, as lower refresh rates may induce cybersickness.
- For VR simulations lasting more than 30 minutes, ensure participants' interpupillary distance (IPD) is measured and set correctly to avoid eye strain and discomfort. Ill-fitted headsets can increase the risk of cybersickness over prolonged use.
- Carefully design the physical research space to eliminate tripping hazards, sharp objects, or any furniture that participants may accidentally collide with while in the VR environment.
- Implement virtual boundary systems (e.g., Oculus Guardian, HTC Chaperone) that alert participants when they approach the edges of the prepared lab space. This minimizes the risk of running into real-world obstacles and walls.
- Avoid equipment setups that block exits or walkways. Ensure that participants can quickly remove headsets and evacuate the area in case of emergencies (e.g., alarms, fire drills).
- Set accompanying audio to an acceptable level that will not induce hearing damage.

### Laboratory Procedures

- Enable screen casting to monitor participants’ behavior in both the physical and virtual environments, as long as it does not impede participants’ experience (e.g., reduce frame rates below comfortable levels). This dual observation ensures quick responses in case of signs of discomfort or physical hazard.
- For VR simulations lasting more than 30 minutes, ensure that participants can take breaks. Long uninterrupted sessions may increase the risk of cybersickness and physical strain.
- Clean headsets and controllers regularly with disinfecting wipes for lenses and UV sanitization for the headset and controllers. Hygiene is crucial for maintaining a safe and healthy environment for all participants.
- Exclude participants with pre-existing physical and/or psychological conditions (e.g., schizophrenia), or known susceptibilities (e.g., epilepsy, severe motion sickness), that could be exacerbated by the VR simulation.

### Managing Cybersickness

With advancements in hardware and improved simulation design, cybersickness—once a common concern—has been greatly minimized. High-quality headsets, along with refined design principles, have significantly reduced issues like nausea, dizziness, and oculomotor discomfort. By also adhering to the following guidelines, the risk of cybersickness can be virtually eliminated.

- Minimize or avoid using artificial locomotion (e.g., joystick-based movement) in favor of natural locomotion (e.g., walking) to reduce cybersickness. If artificial locomotion is necessary, use slow speeds or short bursts.
- Design VR environments with smooth, predictable visual movements to reduce motion-to-visual conflicts that can cause disorientation or nausea.
- Allow participants to gradually acclimate to the virtual environment by starting with simple, low-intensity tasks before progressing to more complex or intense experiences.
- Provide instructions and training to help participants adjust to the controls and navigation methods used in the VR simulation.
- Adopt a comfort rating system to categorize the intensity of the VR simulation and inform participants of the expected comfort level beforehand:

    - **Comfortable:** Seated experience with no locomotion or disorienting effects; suitable for almost all participants. No risk for cybersickness.
    - **Moderate:** May include some locomotion or occasional disorienting effects; suitable for most participants. Minimal risk for cybersickness.
    - **Intense:** Includes lots of locomotion or disorienting effects; not recommended for participants without VR experience. Some risk for cybersickness.

- For moderate or intense VR simulations, provide participants with a space to rest after completing the simulation.
