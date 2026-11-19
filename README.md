# Offensive Security

Generic, vendor-neutral templates for authorized security testing, organised by phase. All examples are fictional (Contoso Ltd., documentation IP ranges, example domains). Use only with written authorization. No commands, payloads or exploits are included.

## Find by phase

| Phase | Folder | What you get | Use it when |
|---|---|---|---|
| Engagement management | [00-engagement-management](./00-engagement-management) | RoE, authorization letter, SOW, evidence handling, tooling | Before any test |
| Reconnaissance | [01-reconnaissance](./01-reconnaissance) | Recon checklist, OSINT worksheet, attack surface inventory | Learning the target |
| Scanning and vulnerability analysis | [02-scanning-and-vulnerability-analysis](./02-scanning-and-vulnerability-analysis) | Vulnerability analysis worksheet | Validating scan results |
| Web and api testing | [03-web-and-api-testing](./03-web-and-api-testing) | Test plan, web and API checklists | Web apps and APIs |
| Network and active directory | [04-network-and-active-directory](./04-network-and-active-directory) | External and internal AD test plans | Networks and directories |
| Cloud testing | [05-cloud-testing](./05-cloud-testing) | Cloud test plan | AWS and Azure |
| Mobile testing | [06-mobile-testing](./06-mobile-testing) | Mobile test plan and checklist | iOS and Android apps |
| Red and purple team | [07-red-and-purple-team](./07-red-and-purple-team) | Exercise plan, scenarios, detection matrix | Testing detection and response |
| Reporting and retest | [08-reporting-and-retest](./08-reporting-and-retest) | Findings, reports, severity guide, remediation, retest, disclosure | After testing |

## How to use

1. Start in `00-engagement-management` and obtain written authorization.
2. Move through the phase folders that match the target.
3. Replace every `<PLACEHOLDER>` with your own values.
4. Review with your own legal and security teams before adopting.

## License
Apache License 2.0. See [LICENSE](./LICENSE).
