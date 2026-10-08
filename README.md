# FTC Troubleshooting Coach AI Agent
An AI-powered diagnostic assistant designed to help FIRST Tech Challenge robotics teams troubleshoot hardware and software issues efficiently. 

*Note: This agent was built using enterprise no-code AI tooling for the Microsoft Agent-a-thon. Due to organizational access constraints, the live agent is restricted to UPB university tenants. This repository serves as an architecture and prompt engineering case study.*

## System Architecture & Prompt Engineering
*   **Platform:** Microsoft Copilot Studio / Agent Builder
*   **Methodology:** No-code agentic orchestration, Retrieval-Augmented Generation (RAG).
*   **Knowledge Base Integration:** Grounded in official FTC documentation, hardware specs (REV/GoBILDA), and common debugging flows.

## Core Capabilities
*   **Hardware Diagnostics:** Guides users through isolation testing for motors, servos, and multiplexed electronics.
*   **Software Debugging:** Assists in identifying logic errors in autonomous and tele-op routines.
*   **Constraint Adherence:** Strictly programmed to provide educational troubleshooting steps rather than just giving away the final answer.

## Repository Contents
*   `system_instructions.md`: The core system prompts defining the agent's persona and logic boundaries.
*   `demo_chat.pdf`: Visual proof of the agent successfully diagnosing a simulated FTC hardware failure.
