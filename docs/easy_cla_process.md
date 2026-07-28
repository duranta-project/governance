# EasyCLA: Signing the Contributor License Agreement

The CLA is managed using the [Linux Foundation EasyCLA tool][easycla-tool].
Contributors can sign the CLA before or after making their first contribution.

To sign the CLA, you need to create an [LFX account][lfx-account]. Corporate
contributors have a dedicated portal in LFX to manage CLAs and check
contribution status.

## Sign the CLA as a Company or Organization

### If your company is registered in the EasyCLA database

Log in with your LFX account to the [LFX EasyCLA dashboard][lfx-dashboard].
Select LFN, then select the Duranta project.

For more information about EasyCLA, see the
[EasyCLA contributor documentation][easycla-contributor-docs].

### If your company is not registered in the EasyCLA database

Contact the LFN support team to add your company name. Then log in with your
LFX account to the [LFX EasyCLA dashboard][lfx-dashboard] and select LFN, then
Duranta.

You will see this message:

> Your organization is not yet enrolled in EasyCLA. For security, please
> contact support via the chat widget.

Use the chatbot to request that your organization's name be added. Adding a new
company takes about 24 to 48 hours.

### CLA Manager

A CLA manager can add more people from the same company as CLA managers. The
CLA manager must add the company's contributors to the "Approved List of
Contributors From My Organization" section. We recommend using the user's
GitHub ID because users sometimes have multiple email addresses.

### Offline Signing of the CLA (Not Recommended)

It is possible to sign the CLA offline if your company is not registered, or
if you have trouble following the procedure above. This option is not
recommended.

**Note**: After signing the PDF version of the CLA, you must still provide
your employees' email addresses, email domains, or GitHub IDs so
their pull requests can pass the EasyCLA check.

If you want to sign the CLA offline, use the PDF version provided in the
[cla folder](../cla). Send the signed copy to
[cicd@durantaproject.org](mailto:cicd@durantaproject.org).

After signing the CLA, you will receive an email inviting you to log in as a
CLA manager. You can later add more people from the same company as CLA
managers. The CLA manager must add the company's contributors to the "Approved
List of Contributors From My Organization" section.

## Sign the CLA with the First Contribution (Individual and Corporate)

When contributors make their first contribution, the pull request (PR) receives
an automated EasyCLA reply if the CLA has not been signed.

The following image shows an example reply:

![EasyCLA Github](./images/Easy_CLA_Github.png)

The reply provides a link to sign the CLA. You should be logged in with your
LFX account before you proceed.

You need to choose which CLA to sign: Corporate Contributor or Individual
Contributor.

![EasyCLA Choice](./images/Easy_CLA_Choice.png)

If you sign as a Corporate Contributor, choose your company name. If you sign
as an Individual Contributor, proceed with the compliance confirmation.

![EasyCLA Corporate](./images/Easy_CLA_Corporate.png)

For more information about EasyCLA, see the
[EasyCLA contributor documentation][easycla-contributor-docs].

### Troubleshooting

If you have issues, contact
[cicd@durantaproject.org](mailto:cicd@durantaproject.org).

[easycla-tool]:
  https://github.com/linuxfoundation/easycla
[easycla-contributor-docs]:
  https://docs.linuxfoundation.org/lfx/easycla/v2-current/contributors
[lfx-account]:
  https://lfx.linuxfoundation.org/
[lfx-dashboard]:
  https://organization.lfx.linuxfoundation.org/
