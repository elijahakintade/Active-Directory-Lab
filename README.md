# Active Directory Lab

## Objective

This lab aims to create an ADDC (Active Directory Domain Controller) automation lab within a SOC (Security Operations Center) automation framework. It is designed to enhance the detection, analysis, and response capabilities of security teams. By leveraging tools such as Splunk, Atomic Red Team, and Crowbar for brute forcing, the lab can simulate realistic attack scenarios and automate responses, thereby improving overall security posture. This approach enhances detection capabilities, improves response times, and promotes continuous security improvement. Integrating these tools into a cohesive automation framework, the ADDC automation lab provides a robust platform for advancing the security operations of an organization.

### Skills Learned

- Using Splunk to collect and analyze machine data from various sources.
- Setting up Splunk dashboards, alerts, and reports for suspicious activities.
- Integrating Splunk with other tools to automate threat responses.
- Using Atomic Red Team to simulate adversary tactics based on MITRE ATT&CK.
- Validating security controls with Atomic Red Team.
- Identifying and fixing gaps in detection and response.
- Using Crowbar to test system resilience against brute force attacks.
- Testing login credential strength with Crowbar.
- Integrating Crowbar into automated testing workflows.
- Deploying AD Domain Controllers and configuring networks and Splunk.
- Running attack simulations with Atomic Red Team and Crowbar.
- Configuring Splunk to detect attacks, generate alerts, and automate responses.
- Analyzing attack simulation results and updating security measures.
- Regularly testing to improve SOC's detection capabilities.
- Automating incident response to reduce reaction times.
- Continuously testing and fixing security gaps for better resilience.

### Tools Used

- Splunk is used for Log Management, Analysis, Security Monitoring, Automation and Orchestration
- Atomic Red Team is an open source library of tests used for Adversary Emulation, Testing and Validation and Continuous Improvement
- Crowbar Brute Forcing Tool is used for Credential Testing and Integration with Automation

I integrated the above tools into the ADDC automation lab to create a cohesive SOC automation framework and to enhance detection, analysis, and response capabilities.

## Steps
*Lab Diagram*

![AD-diagram](https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/41ad80f6-b3c6-43df-af90-69d325a500a8)

<img width="894" alt="Screenshot 2024-04-08 at 10 56 18 PM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/1ac400de-2a24-4650-87df-d77b5674f335">

<img width="870" alt="Screenshot 2024-04-08 at 10 46 48 PM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/6db06b78-162a-4747-81dc-92ebf6a79370">

<img width="816" alt="Screenshot 2024-04-08 at 1 34 29 AM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/85dcf10b-a2e6-4403-98da-d5fcb739f8f2">

<img width="1071" alt="Screenshot 2024-04-06 at 12 30 28 AM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/6e5d4c17-31e0-442f-91fe-893ff1500f55">

<img width="885" alt="Screenshot 2024-04-06 at 2 13 32 AM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/76a5e9c7-dc9d-4a7e-bb53-0f13a9681381">

<img width="1047" alt="Screenshot 2024-04-06 at 2 06 24 AM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/0330541d-5310-4126-8ab9-79bd8570ca25">

<img width="985" alt="Screenshot 2024-04-06 at 1 02 13 AM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/54da08dd-f013-4ec4-9e57-8397a9d63033">

<img width="926" alt="Screenshot 2024-04-05 at 12 15 50 AM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/85efbd74-9247-464f-9d0e-84bcc2b071e0">

<img width="1035" alt="Screenshot 2024-04-04 at 12 28 40 AM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/d7ba9247-ef84-4cd9-af94-d6e09a99b8bf">

<img width="760" alt="Screenshot 2024-04-04 at 11 31 34 PM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/ddf5784f-44bd-4e3f-83d1-189953fc73c8">

<img width="715" alt="Screenshot 2024-04-04 at 10 49 02 PM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/c12d3488-7847-4be9-b84f-fe47dfe66efa">

<img width="761" alt="Screenshot 2024-04-04 at 10 34 16 PM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/b59dee78-682d-4f6f-904d-497d82943b48">

<img width="743" alt="Screenshot 2024-04-04 at 10 24 18 PM" src="https://github.com/elijahakintade/Active-Directory-Lab/assets/68931398/9cf531cc-cf85-4200-b6f5-79cef2d280e6">


