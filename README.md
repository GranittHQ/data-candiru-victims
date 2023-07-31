# Candiru Victim Database

This database tracks details about victims of Candiru's spyware. Each entry represents either an individual or a small group of people, such as a team of lawyers. For that reason, you won’t find a single entry for the "more than 100 victims" [reported](https://www.microsoft.com/en-us/security/blog/2021/07/15/protecting-customers-from-a-private-sector-offensive-actor-using-0-day-exploits-and-devilstongue-malware/) by Microsoft in 2021. The goal is to make each entry as comprehensive as possible by collecting and sorting published reports. The database is updated regularly as more information becomes available.

## How to view the data

To view the data, you can:

* Click on the `.csv` file above to view the data right here on GitHub
* Download a `.zip` file by clicking the green `Code`-button, then view it using Microsoft Excel 
* Download a `.zip` file by clicking the green `Code`-button, then import the `.csv` into Google Sheets

## Schema

Each entry contains information about one victim. An entry may contain information about a small group of people, such as a team of lawyers, until we have enough details to break it down further.

| Field             | Description                                    | Example      |
| ----------------- | ---------------------------------------------- | ------------ |
| `name`            | Name of the victim                             | Sarah Walker |
| `code_name`       | Code name assigned to the victim               | USJRN1       |
| `role`            | Victim's role at the time                      | Journalist   |
| `affiliation`     | Victim's affiliation at the time               | El Faro      |
| `occurred`        | The year the attack occurred                   | 2018         |
| `disclosed`       | When the attack was disclosed                  | 2021-10-24   |
| `disclosed_by`    | Who the attack was disclosed by                | Citizen Lab  |
| `forensics_by`    | Who did the analysis/forensics                 | Lookout      |
| `pegasus_project` | If the victim was named by the Pegasus Project | True         |
| `tech_notified`   | Tech company which notified the victim         | Apple        |
| `device_type`     | Type of device                                 | iPhone       |
| `attack_result`   | If the attack was attempted or successful      | Successful   |
| `lockdown_bypass` | If the attack bypassed Apple's Lockdown Mode   | False        |
| `attack_vector`   | How the spyware was delivered                  | SMS          |
| `exploit_name`    | CVE or name of the exploit used                | KISMET       |
| `first_activity`  | Date of first spyware activity                 | 2018-06-02   |
| `last_activity`   | Date of last spyware activity                  | 2018-07-22   |
| `operator`        | Country operating the spyware                  | Mexico       |
| `sources`         | List of sources                                | amnesty.org  |

## How to contribute

We welcome assistance in making the data as complete as possible. Please reach out with any questions, feedback, updated or missing information, corrections, or requests for new fields. You can open an issue in this repository, or email runa@granitt.io. 

## Licensing

The data is published under an [Attribution-NonCommercial-ShareAlike 4.0 International CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

## About Granitt

Granitt was founded by Runa Sandvik with the goal of securing journalists and at-risk people around the world. To learn more about our work, see this [TechCrunch interview](https://techcrunch.com/2022/07/15/granitt-journalist-security/) from July 2022.
