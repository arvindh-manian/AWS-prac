# Module 2: Cloud Roles

## Spheres of Responsibility 
- Four spheres of responsibility: cloud business management, cloud infrastructure, cloud security, and cloud application infra
- Cloud platform provides value by hosting business applications and data
- Cloud Center of Excellence provides shared services required by business and apps
  - Cloud business office -- onboards people into the cloud platform
  - Common cloud platform shared services
  - Common cloud platform management services
  - Shared services not unique to the cloud platform
- Overarching organization-wide services/processes don't have to reside within the cloud platform
  - Includes first line of support

### Cloud Business Management - Cloud Enterprise Architects
  - within business management sphere
  - works with program manager and financial manager
  - works with architects in other spheres

### Cloud Infrastructure - Cloud Infrastructure Architect
- Designs solution-dependent cloud infra architectures
  - Later built by the cloud infrastructure operations engineer

### Cloud Security - Security Architect
- Specifies security requirements
  - Later managed, monitored, and enforced by security operations engineer

### Cloud Application Infrastructure - Application Architect
- Designs cloud-optimized applications
  - Developed by application engineer
  - Built and automated by DevOps engineer


## Common Duties in the Cloud
<table>
  <tr>
    <td>Duties</td>
    <td>Infrastructure Role</td>
    <td>Application Role</td>
  </tr>
  <tr>
    <td>Design/validate/expand solution-independent architectures and reqs</td>
    <td>Cloud Enterprise Architect</td>
    <td>Cloud Enterprise Architect</td>
  </tr>
  <tr>
    <td>Design/validate/expand solution-dependent architectures and reqs</td>
    <td>Cloud Infrastructure Architect</td>
    <td>Cloud Application Architect</td>
  </tr>
  <tr>
    <td>Build the infrastructure/application</td>
    <td>Cloud Ops Engineer</td>
    <td>App Developer</td>
  </tr>
  <tr>
    <td>Specify security requirements</td>
    <td>Cloud Security Architect</td>
    <td>Cloud Security Architect</td>
  </tr>
  <tr>
    <td>Manage, monitor, and enforce security</td>
    <td>Security Ops</td>
    <td>Security Ops</td>
  </tr>
  <tr>
    <td>Build and manage fast and scalable workflows</td>
    <td>DevOps Engineer</td>
    <td>DevOps Engineer</td>
  </tr>
  <tr>
    <td>Design/build automation solutions</td>
    <td>DevOps Engineer</td>
    <td>DevOps Engineer</td>
  </tr>
  <tr>
    <td>Perform cost coding and cost optimization></td>
    <td>Financial Manager</td>
    <td>Financial Manager</td>
  </tr>
  <tr>
    <td>Manage operational teams</td>
    <td>Program Manager</td>
    <td>Program Manager</td>
  </tr>
</table>

## Cloud Role: Cloud Enterprise Architect
- Responsible for delivering cloud services for businesses
  - Both revenue-generating and internal apps
- Report directly to CIO of Technology
- In charge of entire env
- Understand business services
- Involved w/ entire dev process
- Work w/ business to understand reqs and use cases
- Translate bus reqs and use cases into capabilities
  - Probe information from business leaders
- Use requirements to design solution-independent architectures
- Present diff architecture models
- Maintain the models to guide development work
- Understand organizational view of architecture and verify assumptions with Subject Matter Experts
- Manage/monitor/update models

## Cloud Role: Program Manager
- Ensure cloud is managed appropriately
- Manage assignment of operational roles
- Manage operational teams and suppliers
- Manage and monitor cloud metrics
  - e.g., latency
- Manage service reports

## Cloud Role: Financial Manager
- Manage financial controls of the cloud
- Work in cost center and own cost coding
- In charge of distributing the cost of cloud resources
- Optimize costs by working with business groups
- Make recommendations to business groups

## Cloud Role: Cloud Infrastructure Architect
- Design solution-dependent cloud infra architectures based on busi reqs
- Develop/maintain capacity plans for cloud infra and plans for data and backups
- Advises cloud enterprise architect and works w/ specialists to design cloud infra architectures
- Work with Cloud Center of Excellence

## Cloud Role: Cloud Operations Engineer
- Build/monitor/manage cloud infra and shared services
- Work w/ cloud infra architect on how to buld infra
- Ensure that cloud infra meets service requirements

### Cloud Role: Management
- Manage infra OSs
- Configuration and currency of virtual infra
- Patch and release updates to OSs
- Manage cloud template
- Capture and document changes to templates
- Tag and review cloud infra management details
- Check that virtual infra capacity is available
- Create and manage virtual networks and network connectivity
- Manage resiliency of apps including w/ virtual infra templates

### Cloud Role: Support
- Provide ops support through monitoring, incident response, and incident resolution
- Monitor virtual infra and provide support
- Monitor cloud infra 
- Perform performance tuning
- Respond to incidents and escalate them
- Perform root cause analysis
- Follow incident, change, release, and problem management processes
- Review/modify docs
- Backup and recovery for cloud resources
- Execute disaster recovery procedures
- Monitor/report compliance programs

### Cloud Role: Cloud Security Architect
- Spec security reqs
  - Related to sensitivity of data
- Advise cloud enterprise architect
- Direct security ops engineers to implement sec reqs
- Design/maintain security config checklists, risk assessment plans, security policies, and incident response plans

### Cloud Role: Security Ops Engineer
- Manage/monitor/enforce cloud infra and app security based on reqs
- Ensure workloads comply
- Implement corporate sec policies
- Manage and enforce compliance -- esp. GRC outcomes
- Manage sec configs
  - Use of virtual infra templates
- Certify and approve new templates
- Manage identity and access and integration of identity
- Ensure security groups are configured correctly
- Perform vuln testing and risk analysis
- Create security assessments

### Cloud Role: App Architect
- Design cloud-optimized apps
- Create designs for apps to be created
- Work as technical leaders w/ business development and infra teams
- Work w/ cloud enterprise architect and project teams to develop functional reqs of app
- Define capacity and scaling reqs for app
- Provide deep software knowledge to app devs wrt cloud architecture, design patterns, and programming languages
- Advise on AWS best practices

### Cloud Role: App Dev
- Responsible for code development
- Manage changes to app code base
- Manage release of code into cloud env
- Manage deployment of code into virtual infra and platform services
- Support and monitor performance of app code
- Create/manage app docs
- Develop/doc app optimization techniques
- Provide training for users on apps

### Cloud Role: DevOps Engineer
- Build and operate fast workflows to get apps into cloud
- Deploy and configure daily builds and troubleshoot failed builds
- Communicate w/ devs and PMs
- Support and troubleshoot apps
- Design and build automated solutions for app source, CI/CD pipeline, deployment, and config management systems
- Implement continuous build, integration, deployment, and infra
- Review/recommend improvements to op processes and procedures
- Manage automation tests
- Provide app support
- Develop/maintain change management processes