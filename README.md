ODM Rule Tester
Overview

ODM Rule Tester is a workflow designed to automate the testing and deployment of IBM ODM (Operational Decision Manager) rule projects. It integrates with the IBM ODM Decision Center, Rule Execution Server, and the IBM ODM Management MCP Server to simplify rule validation and deployment activities.

Features
Rule Project Testing
Verify connectivity to ODM servers and MCP server.
Retrieve available decision services from Decision Center.
Analyze rule projects and generate comprehensive test cases.
Export test cases as a .docx document for user review.
Execute test cases against the Rule Execution Server.
Compare expected and actual outputs automatically.
Generate pass/fail results and detailed mismatch reports.
Produce a final test report with execution results and analysis.
Rule Project Deployment
Deploy ODM project .zip files to Decision Center.
Create new decision services or new versions of existing services.
Deploy projects from Decision Center to Rule Execution Server.
Create new RuleApps or new ruleset versions automatically.
Provide deployment verification and troubleshooting information.
Workflow
Testing a Rule Project
Verify server connectivity.
Select a deployed decision service.
Analyze the rule project structure and rules.
Generate comprehensive test cases.
Export test cases for user review.
Execute approved test cases.
Compare expected and actual outputs.
Generate a final testing report.
Deploying a Rule Project
Verify server connectivity.
Upload a project .zip file.
Deploy the project to Decision Center.
Deploy the project to Rule Execution Server.
Verify successful deployment.
Components
Parent Agent

Responsible for:

Environment validation
Project selection
Rule analysis
Test case generation
Report generation
Deployment orchestration
Subagent

Responsible for:

Executing test cases
Capturing actual outputs
Comparing results
Returning structured execution data
Prerequisites
IBM Operational Decision Manager (ODM)
Decision Center running
Rule Execution Server running
IBM ODM Management MCP Server configured and connected
MCP Server

Setup instructions:

https://github.com/DecisionsDev/ibm-odm-management-mcp-server/tree/main

Typical Usage

Test a Rule Project

Connect to ODM servers.
Select a decision service.
Review generated test cases.
Approve execution.
Review final report.

Deploy a Rule Project

Upload project .zip.
Deploy to Decision Center.
Deploy to Rule Execution Server.
Verify deployment results.
Future Enhancements
Test coverage metrics
Automated regression testing
Historical execution tracking
Test result dashboards
CI/CD integration for ODM deployments
