# Trusted Treks – Admin Console Repository

## Purpose
This repository contains all administrative automation and digital workflow tools used to operate Trusted Treks. It is the operational "control panel" for the internal management system.

This repo holds:
- Power Apps application logic
- Power Automate flows
- PowerShell scripts
- Copilot scripts
- Admin setup instructions
- User provisioning
- System configuration sequences

This is where all internal enterprise automation lives.

## Folder Breakdown
- `/powerapps` → Power Apps solutions, components, UI definitions  
- `/powerautomate` → Automated flows for dispatch, scheduling, notifications  
- `/powershell` → Scripts to control Azure, Office365, SharePoint, Graph API  
- `LLM_README.md` → This file  
- `instructions_for_agents.md` → AI interaction rules  

## AI Agents Allowed to Access This Repo
- GPT-1 Operations Controller  
- GPT-2 Dispatch Engine  
- GPT-7 HR & Employee Coach  
- GPT-8 Founder AI  

## AI Tasks Allowed
- Write Power Apps component documentation  
- Generate Power Automate flow logic  
- Create or update PowerShell scripts  
- Provide onboarding workflow instructions  
- Assist with troubleshooting  
- Recommend optimizations  

## AI Tasks NOT Allowed
- Do NOT create or delete flows directly in
