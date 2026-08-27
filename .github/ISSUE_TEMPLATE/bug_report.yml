name: Bug Report
description: Report a reproducible problem with CombatKeepInventory.
title: "[Bug]: "
labels:

- bug

body:

- type: markdown
  attributes:
  value: |
  ## CombatKeepInventory Bug Report
  
  Thank you for taking the time to report a problem.

Before submitting:
- Search existing issues to avoid duplicate reports.
- Make sure you are using a supported Minecraft, Bukkit/Paper, or Velocity version.
- Provide complete logs when possible.
- Do not post private information, server credentials, tokens, or sensitive configuration data.

- type: checkboxes
  id: existing-issues
  attributes:
  label: Existing Issues
  description: Please confirm that you searched the existing issues.
  options:
  - label: I have searched the existing issues and could not find a matching report.
  required: true

- type: dropdown
  id: plugin-version
  attributes:
  label: CombatKeepInventory Version
  description: Which version of CombatKeepInventory are you using?
  options:
  - "1.1.0"
  - "Other"
  validations:
  required: true

- type: dropdown
  id: platform
  attributes:
  label: Affected Platform
  description: Where does the problem occur?
  options:
  - Bukkit / Paper
  - Velocity
  - Bukkit / Paper + Velocity
  - Other
  validations:
  required: true

- type: input
  id: minecraft-version
  attributes:
  label: Minecraft Version
  description: Enter the exact Minecraft version.
  placeholder: "Example: 1.21.11"
  validations:
  required: true

- type: input
  id: server-software
  attributes:
  label: Server Software
  description: Enter the exact server implementation and version.
  placeholder: "Example: Paper 1.21.11"
  validations:
  required: true

- type: input
  id: velocity-version
  attributes:
  label: Velocity Version
  description: If Velocity is used, provide the exact Velocity version. Otherwise enter N/A.
  placeholder: "Example: Velocity 3.4.x"
  validations:
  required: true

- type: input
  id: java-version
  attributes:
  label: Java Version
  description: Provide the output of java -version.
  placeholder: "Example: Java 21.0.x"
  validations:
  required: true

- type: textarea
  id: description
  attributes:
  label: Bug Description
  description: Clearly describe what is going wrong.
  placeholder: |
  Describe the problem in detail.
  Include what happens and when it happens.
  validations:
  required: true

- type: textarea
  id: expected
  attributes:
  label: Expected Behavior
  description: Describe what you expected CombatKeepInventory to do.
  placeholder: |
  Example:
  The player's inventory should be kept when they die outside combat.
  validations:
  required: true

- type: textarea
  id: actual
  attributes:
  label: Actual Behavior
  description: Describe what CombatKeepInventory actually does.
  placeholder: |
  Example:
  The inventory is dropped even though the player was not in combat.
  validations:
  required: true

- type: textarea
  id: reproduction
  attributes:
  label: Steps to Reproduce
  description: Provide the smallest reliable sequence of steps that reproduces the problem.
  placeholder: |
  1. Start the server with ...
  2. Join with ...
  3. Execute ...
  4. Attack another player ...
  5. Disconnect ...
  6. Observe ...
  validations:
  required: true

- type: textarea
  id: logs
  attributes:
  label: Relevant Logs
  description: |
  Paste the relevant server/proxy log output.
  
  Please include the complete exception and stack trace when applicable.
  
  render: text
  placeholder: |
  Paste relevant logs here.
  validations:
  required: true

- type: textarea
  id: configuration
  attributes:
  label: Relevant Configuration
  description: |
  Paste only the configuration sections relevant to the problem.
  
  Remove passwords, tokens, IP addresses, private information, or other sensitive data.
  
  render: yaml
  placeholder: |
  Paste relevant config.yml sections here.
  validations:
  required: false

- type: checkboxes
  id: integrations
  attributes:
  label: Integrations
  description: Select the integrations currently involved in the affected server.
  options:
  - label: WorldGuard
  - label: PvPManager
  - label: Geyser
  - label: Floodgate
  - label: Velocity
  - label: Other combat/death/inventory plugin
  - label: None

- type: textarea
  id: other-plugins
  attributes:
  label: Related Plugins
  description: |
  List plugins that may interact with combat, death, inventory, teleportation,
  server switching, or proxy communication.
  placeholder: |
  Example:
  - WorldGuard
  - PvPManager
  - Geyser
  - Floodgate
  - OtherPlugin 1.0.0
  validations:
  required: false

- type: dropdown
  id: reproduction-frequency
  attributes:
  label: Reproduction Frequency
  description: How consistently can you reproduce the problem?
  options:
  - Always
  - Frequently
  - Sometimes
  - Rarely
  - Unable to reproduce consistently
  validations:
  required: true

- type: dropdown
  id: scope
  attributes:
  label: Affected Players
  description: Who is affected by the problem?
  options:
  - All players
  - Java players only
  - Bedrock players only
  - Specific players
  - Only when using Velocity
  - Only when not using Velocity
  - Unknown
  validations:
  required: true

- type: textarea
  id: additional-context
  attributes:
  label: Additional Context
  description: Provide screenshots, videos, crash reports, timings, or any other information that may help diagnose the issue.
  placeholder: |
  Add any additional information here.

- type: checkboxes
  id: verification
  attributes:
  label: Verification
  description: Please confirm the following.
  options:
  - label: I can reproduce this problem on the stated configuration.
  required: true
  - label: I have provided the relevant logs and reproduction steps.
  required: true
  - label: I have removed sensitive information from the report.
  required: true
