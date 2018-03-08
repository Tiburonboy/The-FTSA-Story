Introduction
====
Last update: 6 February 2018

This is a story about a project that spans more than 20 years. I wasn't involved in the beginning and I retired before the effort was completed, but I was there for much of the middle parts. This is a history of the development of a Flight Termination Safe and Arm (FTSA) device.  Later I’ll explain what those acronyms mean.  The use of acronyms is very popular in this industry.  

I’ve been thinking about writing this story for several years and I was going to write a lessons learned paper or some sort of case study.  So for a while now, I’ve been collecting background information with the thought of one day writing the history of this project.  

When the United States military wants to test a new weapon or upgrades, it often performs the tests at a military test range. There are about 15 large test ranges where test and evaluation takes place in controlled arena.  The ranges are equipped with radars, telemetry receiving equipment and other instrumentation necessary for these tests.  A test article, be it an airplane, missile, bomb or drone is usually instrumented so that the guidance or control functions on the test item can be monitored and the data analyzed.  If the test article is a one time usage device like a missile or bomb, the data is transmitted to ground stations during the flight.  Sometime it is necessary to have a method of terminating the flight of a missile if things go wrong.  A flight termination system is the name given to a collection of equipment that is used to remotely end the flight of a missile or test article that is not operating correctly and posses a threat to life or property.  

This story is about the design and development of one of the components of the flight termination system called the Flight Termination Safe and Arm (FTSA) device.  The story will also touch on areas such as some of my experiences working as a civil servant for the US Navy for 35 years and the design of a new telemetry system for an air to ground missile called the High Speed Anti-Radiation Missile (HARM).    

The FTSA is an interesting component because it is an electronic device that initiates the explosive chain leading to the destruct charge in a flight termination system.  As an electrical engineer the development of device to initiate an explosive component was a new area that was very interesting and outside the realm of anything that I had worked on before.

<p align="center">***</p>

(this is prolog stuff)
A short explanation of some aspects of weapons testing is necessary to set the stage and put things in context before jumping into the story, otherwise the story might get lost in the weeds without a high level view of the surrounding landscape. Here is a brief introduction to the major characters and concepts in this story.

**Major Range and Test Facility Base**  
There are a collection of major military bases that have been characterized by the DoD as national assets, since they support development and deployment of U.S. warfighting capabilities. There are about 15 in total with about five for each service.  The base I worked at is one of these MRTFB bases and is called the Naval Air Warfare Center Weapons Division located at Point Mugu and China Lake, California. Most of these bases have instrumented test ranges, which are large open area facilities used for test and evaluation of weapon systems in a controlled environment.  In order to test a new system on a range, the equipment being tested must be compatible with the infrastructure on that range.  

The MRTFB ranges have standardized systems so that common methods of data collection and instrumentation can be shared to improve efficiency and promote compatibility amount the test ranges. Standardized telemetry, recording and flight safety systems have been adopted.  There are two documents in particular that are relevant, IRIG-106 and RCC 319.  IRIG stands for Inter Range Instrumentation Group and defines the telemetry requirements for equipment used on the MRTFB ranges.  RCC stands for Range Commander Counsel and under that name a large collection of standards for equipment usage on the ranges is published.  RCC 319 defines the range safety requirements for systems to be tested on the range.  In particular are in the flight termination system requirements.  The need for flight termination systems will be discussed later.

**Central Test and Evaluation Investment Program**  
The Central Test and Evaluation Investment Program (CTEIP) is an office under the Secretary of Defence responsible for funding some of the test and evaluation needs at the MRTFB ranges.  CTEIP focuses on projects that improve the test capabilities, development of near-term solutions to test capability shortfalls and foster opportunities for joint efforts while avoiding unwarranted duplication of test capabilities.  Programs and services would submit proposals to CTEIP for funding and CTEIP would prioritise the needs and fund the most critical efforts.  CTEIP was the funding sponsor for the JAMI program describe below. 

**Joint Advanced Missile Instrumentation**  
The Joint Advanced Missile Instrumentation (JAMI) was a CTEIP project that developed several products related to testing missiles.  On of these projects was the flight termination safe and arm device.  

**Flight Termination Safe and Arm**  

**Command Destruct**


Navair

NAWC

Kaman Aerospace
https://en.wikipedia.org/wiki/Kaman_Aircraft


**Telemetry**  
Telemetry is the science of remote monitoring.  Various parameters on a test article are instrumented and the data is transmitted wirelessly to a receiving site for collection, analysis and storage.  On the DoD ranges the transmission of data is by radio waves.  The instrumentation that collects the data, formats and tramits it to the receiving site is called the telemetry system.  In air to air and air to ground missiles, the telemetry system often is placed where the missile warhead would reside.  In other words, the war head is removed and the telemetry systems takes the place of the war head since there is usually not much extra available space for both the warhead and the telemetry system.  The acronym TM is often used to refer to the telemetry system.

**High Speed Anti-Radiation Missile**  
The High Speed Anti-Radiation Missile (HARM) is a air-to-surface missile designed to home in on electronic transmissions coming from surface-to-air radar systems. The development of a new telemetry system for the HARM is the impetus for the development of the safe and arm device.

**Range Safety**  
Range Safety is an organization that evaluates and is responsible for range safety under the authority of the base commanding officer.  Since weapon testing can sometimes be inherently dangerous or destructive, testing must be performed in a safe and controlled way.  Ideally the unintended loss of life or destruction of property must be as close to zero in probability as possible.  Extensive analysis and planning prior to testing is required to ensure that systems under test are safe.   

**System Safety**  
System Safety is an organization that evaluates the safety of maned systems for testing.  This organization is seperate from range safety. They are responsible for evaluating the risks to maned systems during weapon testing and deployment.  
Name the system safety groups
NNMCI
WESERB

**Flight Termination System**  
A Flight Termination System (FTS) is a collection of components that can be used to remotely terminate or end the flight of a wayward test article.  A flight termination system can be part of the telemetry system but it doesn’t have to be, but remote monitoring of the status of the FTS is required, so it usually is adjunct to the TM system.  The FTS has stringent reliability, design and testing requirements so some independence is usually maintained to other non-FTS systems.
