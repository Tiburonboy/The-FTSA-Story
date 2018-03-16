Prologue  
=======
Last update: 10 March 2018  

This story is about the development of a small electronic device called a flight termination safe and arm device.  A short explanation of some aspects of weapons testing by the United States (US) Department of Defense (DoD) is necessary to set the stage and put things in context before jumping into the story, otherwise the story might get lost in the weeds without a high level view of the surrounding landscape. Here is a brief introduction to the major characters and concepts in this story.  

**Major Range and Test Facility Base**  
There are a collection of major military bases that have been characterized by the DoD as national assets, since they support development and deployment of U.S. warfighting capabilities. There are about 15 in total with about five for each service.  The base I worked at is one of these MRTFB bases and is called the Naval Air Warfare Center Weapons Division located at Point Mugu and China Lake, California. Most of these bases have instrumented test ranges, which are large open area facilities used for test and evaluation of weapon systems in a controlled environment.  In order to test a new system on a range, the equipment being tested must be compatible with the infrastructure on that range.  

The MRTFB ranges have standardized systems so that common methods of data collection and instrumentation can be shared to improve efficiency and promote compatibility amount the test ranges. Standardized telemetry, recording and flight safety systems have been adopted.  There are two documents in particular that are relevant, IRIG-106 and RCC 319.  IRIG stands for Inter Range Instrumentation Group and defines the telemetry requirements for equipment used on the MRTFB ranges.  RCC stands for Range Commander Counsel and under that name a large collection of standards for equipment usage on the ranges is published.  RCC 319 defines the range safety requirements for systems to be tested on the range.  In particular are in the flight termination system requirements.  The need for flight termination systems will be discussed later.  

**Central Test and Evaluation Investment Program**  
The Central Test and Evaluation Investment Program (CTEIP) is an office under the Secretary of Defence (SecDef) responsible for funding some of the test and evaluation needs at the MRTFB ranges.  CTEIP focuses on projects that improve the test capabilities, development of near-term solutions to test capability shortfalls and foster opportunities for joint efforts while avoiding unwarranted duplication of test capabilities.  Programs and services would submit proposals to CTEIP for funding and CTEIP would prioritise the needs and fund the most critical efforts.  CTEIP was the funding sponsor for the JAMI program describe below. 

**Joint Advanced Missile Instrumentation**  
The Joint Advanced Missile Instrumentation (JAMI) was a CTEIP project that developed several products related to testing missiles.  One of these projects was the FTSA device.  The JAMI program office was located at the Naval Air Warfare Center at China Lake.

The initial FTSA production effort was accomplished under a cooperative research and development agreement between the NAWC and Kaman Aerospace, Fuzing and Safety Systems, who at that time was operating under the name Raymond Engineering. They agreed to take the original Navy FTSA design and produce first article units for qualification testing.  That effort is describe later.

**Flight Termination Safe and Arm**  
A Flight Termination Safe and Arm (FTSA) is a device that keeps a destruct charge from inadvertently initiating and only arming after specific conditions are satisified. Older devices were electro-mechanical devices that prevented arming by having components or contacts rotated out out of alignment in the safe position and then under acceleration or by pulling a lanyard the components would be in alignment and the device would be able to fire.  New FTSA devices are electronic and the explosive components can be in-line. Electronic switches keep the device in the safe state until certain conditions are met.  

**Command Destruct System**  
Command destruct is the term used to describe an action to terminate the flight of a test article and the system is a collection of components used to accomplish this action. A Flight Termination System and a Command Destruct System are synonymous when talking about range safety systems.

**Naval Air Systems Command**  
The Naval Air Systems Command (NAVAIR) provides support for research, design and development of aircraft, weapons and systems operated by the US Navy and Marines. NAVAIR is headquartered at Patuxent River, Maryland.  NAVAIR is the parent command of the Naval Air Warfare Center Weapons Division where I work. These days the whole enterprize is branded as NAVAIR.  

**Naval Air Warfare Center, Weapons Division**  
In 1990, the activities of the Pacific Missile Test Center at Point Mugu CA and the Naval Weapons Center at China Lake CA were merged under one command and became the Naval Air Warfare Center, Weapons Division (NAWC-WD).

**Raymond Engineering**  
Raymond Engineering was founded in 1938 and is located in Middletown CT. Raymond became a part of Kaman Corporation in 1986 and was merged with Kaman Aerospace Corporation in January of 1995. It’s now called Kaman Fuzing or Fuzing and Safety Systems.  The original CRADA was with Raymond Engineering.

**Kaman Aerospace, Fuzing and Safety Systems**  
Kaman Aerospace, Fuzing and Safety Systems develops and manufactures Safe/Arm Devices, Fuzes, Motor Igniters, Flight Termination Devices and other related equipment. This group supplies fuzes for Tomahawk, Harpoon, AMRAAM, STANDARD Missile, SLAM-ER, Maverick, Brimstone, and many other programs.  Raymond Engineering became a part of Kaman Aerospace in 1986.

**Telemetry**  
Telemetry is the science of remote monitoring.  Various parameters on a test article are instrumented and the data is transmitted wirelessly to a receiving site for collection, analysis and storage.  On the DoD ranges the transmission of data is by radio waves.  The instrumentation that collects the data, formats and tramits it to the receiving site is called the telemetry system.  In air to air and air to ground missiles, the telemetry system often is placed where the missile warhead would reside.  In other words, the war head is removed and the telemetry systems takes the place of the war head since there is usually not much extra available space for both the warhead and the telemetry system.  The acronym TM is often used to refer to the telemetry system.

**High Speed Anti-Radiation Missile**  
The High Speed Anti-Radiation Missile (HARM) is a air-to-surface missile designed to home in on electronic transmissions coming from surface-to-air radar systems. The development of a new telemetry system for the HARM is the impetus for the development of the safe and arm device.

**Range Safety**  
Range Safety is an organization that evaluates and is responsible for range safety under the authority of the base commanding officer.  Since weapon testing can sometimes be inherently dangerous or destructive, testing must be performed in a safe and controlled way.  Ideally the unintended loss of life or destruction of property must be as close to zero in probability as possible.  Extensive analysis and planning prior to testing is required to ensure that systems under test are safe.   

**System Safety**  
System Safety is an organization that evaluates the safety of maned systems for testing.  This organization is seperate from range safety. They are responsible for evaluating the risks to maned systems during weapon testing and deployment.  The Navy, Air Force and Army each have their own system safety offices.  The FTSA program was required to present design reviews to the Air Force System Safety Office at Eglin Air Force Base in Florida.  This office is called the Nonnuclear Munitions Safety Board (NMSB).  This office rejected the first FTSA design and a re-design of the FTSA was required.  The Air Force was involved since the FTSA was being flown on an Air Force F-16.  At the time, there were no plans for the device to be used on weapons flown from Navy carriers, so the Navy’s Weapon System Explosives Safety Review Board (WSESRB) refused to review the design saying it was outside their charter.  The System Safety Office at China Lake did provide a limited review of the FTSA’s safe separation time.

**Flight Termination System**  
A Flight Termination System (FTS) is a collection of components that can be used to remotely terminate or end the flight of a wayward test article.  A flight termination system can be part of the telemetry system but it doesn’t have to be, but remote monitoring of the status of the FTS is required, so it usually is adjunct to the TM system.  The FTS has stringent reliability, design and testing requirements so some independence is usually maintained to other non-FTS systems.

