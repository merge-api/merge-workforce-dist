# Merge Workforce Desktop Client

Bring your organization's approved AI tools to employee desktops. The Merge Workforce desktop client helps IT teams configure AI access, apply organizational policies, and understand AI usage across managed macOS and Windows devices.

[Download installers](https://github.com/merge-api/merge-workforce-dist/releases) · [Deployment guide](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/deployment-overview) · [Explore Merge for Workforce](https://www.merge.dev/workforce)

## Get started

**IT administrators:** Start with [Plan your deployment](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/deployment-overview) for requirements, organization setup, and rollout instructions.

1. **Set up your organization.** Visit [Merge for Workforce](https://www.merge.dev/workforce) to get started, or sign in to your existing Merge organization. Configure SSO and SCIM before deploying to employees.
2. **Prepare device enrollment.** In your dashboard, open **Devices → Deployment** to generate an enrollment token and obtain your deployment configuration. Keep the token in your managed deployment system.
3. **Choose your installer.** Open [Releases](https://github.com/merge-api/merge-workforce-dist/releases), select a release, and expand **Assets**. Download the `.pkg` for macOS or `.msi` for Windows. Read that release's notes for availability and limitations.
4. **Deploy through your device management platform.** Follow the appropriate guide below to distribute the installer and configuration together. Begin with a small test group in observe mode, verify enrollment, then expand your rollout.

**Employees:** Follow your IT team's installation and sign-in instructions. Your organization supplies the configuration needed to connect your device to Merge.

## Deploy to your workforce

| Your device management platform | Instructions |
| --- | --- |
| Microsoft Intune | [Deploy with Intune](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/deploy/intune) |
| Jamf Pro | [Deploy with Jamf](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/deploy/jamf) |
| Iru | [Deploy with Iru](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/deploy/iru) |
| Mosyle | [Deploy with Mosyle](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/deploy/mosyle) |
| Group Policy or Microsoft Configuration Manager | [Deploy with Group Policy or Configuration Manager](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/deploy/gpo-and-configuration-manager) |
| Omnissa Workspace ONE | [Deploy with Workspace ONE](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/deploy/workspace-one) |
| Another MDM | [Deploy with any other MDM](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/deploy/other-mdm) |

## Release availability

This repository currently contains preview releases. Review the release notes and confirm the appropriate version with your Merge representative before a production rollout.

- **macOS:** The `v0.1.0-preview3` release includes a `.pkg` described in its release notes as signed and notarized.
- **Windows:** The available `v0.1.0-preview1` `.msi` is an unsigned evaluation preview, not a production deployment package. A signed Windows release is pending.

## Documentation and support

- [Desktop client overview](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/overview)
- [Privacy and data collection](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/privacy-and-data-collection)
- [Employee FAQ](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/employee-faq)
- [Troubleshooting](https://docs.merge.dev/merge-agent-handler/workforce-desktop-client/troubleshooting)

For help with account access or your rollout, contact your Merge representative. New to Merge? [Learn about Merge for Workforce](https://www.merge.dev/workforce).
