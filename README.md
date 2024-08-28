# Bulk Section in MITRE Navigator

This tool allows users to input multiple `techniqueID` and `tactic` values, each on a new line, and dynamically generate a JSON file compatible with the MITRE ATT&CK Navigator. The tool includes input validation for tactics and offers options to copy or download the generated JSON file.

## Features

- **Technique ID Input:** Users can enter multiple technique IDs, each on a new line.
- **Tactic Input:** Users can enter multiple tactics, each on a new line. Only specific tactics are allowed.
- **Input Validation:** The tool checks each tactic against a predefined list of allowed tactics. If any invalid tactics are entered, an error message is displayed, guiding the user to correct the input.
- **Generate JSON:** Users can generate a JSON file that includes the provided technique IDs and tactics.
- **Copy JSON:** The generated JSON can be copied to the clipboard for easy sharing.
- **Download JSON:** Users can download the generated JSON file as `mitre-navigator.json`.
- **MITRE Navigator Link:** A direct link to the MITRE ATT&CK Navigator is provided for quick access.

## Allowed Tactics

The following tactics are accepted:

- `resource-development`
- `initial-access`
- `execution`
- `persistence`
- `privilege-escalation`
- `defense-evasion`
- `credential-access`
- `discovery`
- `lateral-movement`
- `collection`
- `command-and-control`
- `exfiltration`
- `impact`

## Usage

1. **Enter Technique IDs:**
   - In the "Technique ID" textarea, input one technique ID per line.

2. **Enter Tactics:**
   - In the "Tactic" textarea, input one tactic per line. Each tactic must match one of the allowed tactics listed above.

3. **Generate JSON:**
   - Click the "Generate JSON" button to
