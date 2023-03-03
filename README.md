# Candiru Victim Database

Granitt is tracking details about victims of Candiru's spyware based on publicly available information. This database is focused on individuals and small groups of people, so you won't find a single entry for the "more than 100 victims" [reported](https://www.microsoft.com/en-us/security/blog/2021/07/15/protecting-customers-from-a-private-sector-offensive-actor-using-0-day-exploits-and-devilstongue-malware/) by Microsoft in 2021. The goal is to make the records as comprehensive as possible by collecting and sorting published reports. The database is updated regularly as more information becomes available.

## How to view the data

To view the data, you can:

* Click on the `.csv` file above to view the data right here on GitHub
* Download a `.zip` file by clicking the green `Code`-button, then view it using Microsoft Excel 
* Download a `.zip` file by clicking the green `Code`-button, then import the `.csv` into Google Sheets

## Schema

Each row in the database contains information about one alleged victim. A row may contain information about small groups of victims, such as a team of lawyers or employees at a media organization, until we have enough details to break it down further.

| **Field**           | Description                       | Type    | Example          |
| ------------------- | --------------------------------- | ------- | ---------------- |
| `name`              | Name of the victim                | String  | `John Doe`       |
| `code_name`         | Code name assigned to the victim  | String  | `FRJRN1`         |
| `role`              | Victim's role at the time         | String  | `Staff`          |
| `organization`      | Victim's organization at the time | String  | `Vocdoni`        |
| `occurred`          | Year the case occurred            | String  | `2019`           |
| `disclosed`         | Year the case was disclosed       | String  | `2021`           |
| `disclosed_by`      | Who the case was disclosed by     | String  | `Citizen Lab`    |
| `forensics_by`      | Who did the analysis/forensics    | String  | `Microsoft`      |
| `apple_warning`      | If Apple sent a warning    | Boolean | `FALSE` |
| `device_os`         | Operating system on the device    | String  | `Windows`        |
| `attack_attempted`  | If an attack was attempted        | Boolean | `TRUE`           |
| `attack_successful` | If an attack was successful       | Boolean | `TRUE`           |
| `attack_vector`     | How the spyware was delivered     | String  | `Email`          |
| `exploit_name`      | Name of the exploit used          | String  | `CVE-2021-31979` |
| `first_activity`    | Date of first spyware activity    | String  | `2019-06-02`     |
| `last_activity`     | Date of last spyware activity     | String  | `2020-07-22`     |
| `operator`          | Country operating the spyware     | String  | `Spain`          |
| `sources`           | List of sources                   | String  | `granitt.io`     |

## How to contribute

We welcome assistance in making the data as complete as possible. Please reach out with any questions, feedback, updated or missing information, corrections, or requests for new fields. You can open an issue in this repository, or email runa@granitt.io. 

## Licensing

The data is published under an [Attribution-NonCommercial-ShareAlike 4.0 International CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

## About Granitt

Granitt was founded by Runa Sandvik with the goal of securing journalists and at-risk people around the world. To learn more about our work, see this [TechCrunch interview](https://techcrunch.com/2022/07/15/granitt-journalist-security/) from July 2022.
