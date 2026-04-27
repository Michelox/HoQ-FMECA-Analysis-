# HoQ-FMECA-Analysis-

This project presents a Quality Engineering analysis for the conceptual design and risk assessment of a smart robotic vacuum cleaner targeted at families with children and pets. The study applies structured design and reliability methodologies to translate customer needs into technical characteristics, benchmark the product against market competitors, and identify the most critical failure modes affecting product performance and user satisfaction.

The project was developed as part of the Quality Engineering course at Politecnico di Torino and focuses on the early-stage design of a domestic cleaning robot capable of meeting the specific needs of households characterized by frequent cleaning requirements, pet hair, food residues, allergens, and the need for safe and quiet operation.

## Project Overview

The increasing adoption of smart home technologies has changed customer expectations for household appliances. Robot vacuum cleaners are no longer evaluated only on cleaning ability, but also on autonomy, navigation intelligence, noise level, app connectivity, reliability, and ease of use.

This project investigates how a robotic vacuum cleaner can be designed to better satisfy the needs of families with children and pets. These users typically require a device that can clean multiple floor types, handle pet hair and dirt, operate safely around children and animals, cover large areas, and reduce the need for manual intervention.

To support this objective, the project combines two main Quality Engineering tools:

- **House of Quality (HoQ)**, used to convert customer requirements into measurable technical characteristics.
- **Failure Mode, Effects and Criticality Analysis (FMECA)**, used to identify potential failures, evaluate their criticality, and prioritize risk mitigation actions.

## Target Market Segment

The selected market segment consists of modern families with children aged 0–12 and one or more household pets, mainly dogs or cats. This segment was chosen because these households usually experience higher cleaning frequency and stronger hygiene requirements than other user groups.

Typical characteristics of the target segment include:

- Medium to large homes with different floor surfaces, such as tiles, hardwood floors, and carpets.
- Frequent accumulation of food residues, dust, pet hair, and dirt.
- High sensitivity to allergens and hygiene-related concerns.
- Preference for automated, reliable, and low-maintenance cleaning solutions.
- Interest in smart home integration and app-based control.
- Need for quiet and safe operation around children and pets.

## Customer Requirements

The project starts from Voice of the Customer statements and translates them into a structured set of customer requirements. These requirements represent what users expect from the robotic vacuum cleaner.

The final customer requirements include:

- Strong suction power
- Ability to clean all floor types
- Smart navigation system
- Automatic recharge and resume
- Wide area coverage
- Energy efficiency and eco-friendly operation
- Low noise level
- Ease of use for all users
- Lightweight and compact design
- Long component lifetime
- Mobile app control
- Smart mapping visualization
- Notifications and alerts
- Efficient cleaning kit

These requirements were grouped into categories related to system design needs, comfort, structural needs, and additional functionalities.

## House of Quality Analysis

The House of Quality was used to connect customer requirements with technical characteristics. This allowed the project team to identify which engineering parameters have the strongest influence on customer satisfaction.

The main technical characteristics analyzed were:

- Motor power
- Airflow rate
- SLAM localization accuracy
- SLAM update range
- Path optimization metric
- Auto recharge time
- Battery capacity
- Acoustic noise level
- Component lifetime
- Setting steps

Each technical characteristic was evaluated based on its relationship with the customer requirements. The project applied importance weighting, competitive benchmarking, and normalization methods to determine the most relevant technical priorities.

## Competitive Benchmarking

The proposed robotic vacuum cleaner concept was benchmarked against three existing competitors:

- Dyson 360 Vis Nav
- iRobot Roomba j7+
- Roborock S8

The benchmarking analysis compared the proposed product with these competitors across both customer requirements and technical characteristics. This helped identify the areas where the product performs competitively and the areas requiring improvement.

The analysis showed that the proposed model performs well in several important areas, such as motor power, acoustic noise level, battery capacity, and recharge time. However, it also revealed weaknesses in SLAM update range, airflow rate, and component lifetime, which were identified as critical areas for further development.

## Q-Bench and ELECTRE II Optimization

A decision-support procedure was developed using a Q-Bench-style approach combined with the ELECTRE II outranking method. The goal was to identify an improved technical configuration within predefined design limits.

The algorithm evaluated possible combinations of technical characteristics and selected the best configuration based on weighted criteria and outranking logic. The optimized solution did not correspond to any competitor model, suggesting the possibility of a differentiated product configuration with stronger performance across the selected criteria.

This part of the project demonstrates how multi-criteria decision-making tools can support product concept selection and technical target definition.

## FMECA Analysis

The second major part of the project is the Failure Mode, Effects and Criticality Analysis. FMECA was used to identify potential failure modes of the robotic vacuum cleaner and assess their impact on system performance, safety, and user experience.

The analysis focused on key components and functions, including:

- Sensors for obstacle detection
- Wheel motors for movement and locomotion
- Battery for power supply
- Bluetooth module for connectivity
- Filter for airflow and debris collection

For each failure mode, the project identified:

- The affected function
- The operational mode
- The possible failure effect
- The severity of the failure
- The possible failure causes
- The probability of occurrence
- The available detection system
- The detectability rating
- The Risk Priority Number

## Risk Priority Number

The Risk Priority Number was calculated using severity, occurrence, and detectability ratings. This allowed the project team to rank the most critical failure causes and prioritize corrective actions.

The analysis showed that the most critical risks were related mainly to wheel motor malfunction and filter clogging. In particular, hair wrapped around the wheels represented one of the highest-priority issues because it can strongly affect movement and robot functionality.

Other relevant risks included reduced suction due to clogged filters, battery degradation, sensor failures, and communication loss between the robot and the mobile application.

## Criticality Matrix

A criticality matrix was created to visualize the relationship between severity and occurrence for the identified failure modes. Detectability was also considered by representing it through the size of each plotted point.

This matrix helped identify which failures require the most urgent attention and provided a clear visual summary of the system’s main reliability concerns.

## Key Findings

The project produced several important findings:

- Families with children and pets represent a strong target market for smart robotic vacuum cleaners due to their need for frequent, automated, and hygienic cleaning.
- The most important customer requirements are related to suction power, floor compatibility, smart navigation, automatic recharge, and energy efficiency.
- Battery capacity and component lifetime are among the most influential technical characteristics for customer satisfaction.
- Competitive benchmarking revealed that the proposed model has good potential but requires improvement in airflow rate, SLAM update range, and component lifetime.
- The Q-Bench and ELECTRE II optimization process generated a technical configuration that improves the product concept beyond the benchmarked competitors.
- FMECA showed that wheel motor malfunction and filter clogging are among the most critical reliability risks.
- Preventive maintenance, better component protection, improved monitoring, and enhanced detection systems are essential to improve product reliability.

## Methodologies Used

This project applies the following methods and tools:

- Market segment analysis
- Voice of the Customer analysis
- Customer Requirement Tree
- House of Quality
- Competitive benchmarking
- Technical characteristic prioritization
- Lyman’s normalization
- Q-Bench optimization
- ELECTRE II multi-criteria decision analysis
- Failure Mode, Effects and Criticality Analysis
- Risk Priority Number calculation
- Criticality matrix

## Project Structure

The report is organized into the following main sections:

1. Introduction  
2. Market Segment Determination  
3. House of Quality  
4. House of Quality Final Design  
5. FMECA Methodology  
6. Discussion  
7. Conclusion  
8. References  
9. Appendices  

The appendices include additional supporting material, such as customer requirement paths, survey histograms, customer requirement weights, benchmarking tables, formulas, relationship matrices, and the Q-Bench optimization profile.

## Academic Context

This project was developed for academic purposes within the Quality Engineering course at Politecnico di Torino. It demonstrates the application of quality design tools and reliability analysis methods to a real-world consumer product concept.

The work provides a structured example of how customer needs, technical design parameters, competitive analysis, and failure risk assessment can be integrated during the early stages of product development.

## Conclusion

The project shows how Quality Engineering methodologies can support the development of a smart robotic vacuum cleaner by aligning product design with customer expectations and reliability requirements.

Through the House of Quality, the analysis translates user needs into measurable technical priorities. Through FMECA, it identifies the most critical failure modes and supports risk-based decision-making. Together, these tools provide a solid foundation for future product development, design improvement, and prototype validation.
