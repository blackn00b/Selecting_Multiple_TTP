# Bulk Scoring in MITRE Navigator

This project provides a user-friendly HTML page for generating a JSON file based on inputted MITRE ATT&CK Tactics and Techniques. It allows users to input technique IDs and tactics in bulk, validate the tactics against an allowed list, and generate a JSON output that can be copied or downloaded.

## Features

- **Bulk Input**: Users can input multiple technique IDs and tactics, each on a new line.
- **Input Sanitization**: The entered tactics are validated against a predefined list of allowed tactics.
- **Score Integration**: Users can input a score that is added under each tactic in the generated JSON.
- **JSON Output**: The JSON output can be viewed, copied, or downloaded.
- **MITRE Navigator Link**: A direct link to the [MITRE ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/) is provided.

## Allowed Tactics

The following tactics are allowed in the input:

- reconnaissance
- resource-development
- initial-access
- execution
- persistence
- privilege-escalation
- defense-evasion
- credential-access
- discovery
- lateral-movement
- collection
- command-and-control
- exfiltration
- impact

## How to Use

1. **Enter Technique IDs**: Input the technique IDs, one per line.
2. **Enter Tactics**: Input the corresponding tactics, one per line. Ensure the tactics are from the allowed list.
3. **Enter Score**: Provide an integer score that will be included in the JSON under each tactic.
4. **Generate JSON**: Click the "Generate JSON" button to create the JSON output.
5. **Copy or Download JSON**: You can copy the JSON to your clipboard or download it as a file.

## Project Link

You can access the project online via the following link:

[Bulk Scoring in MITRE Navigator](https://blackn00b.github.io/Selecting_Multiple_TTP/)

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for any improvements or bug fixes.

## License

This project is open-source and available under the MIT License.
