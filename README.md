# iOS xcodeproj update for manual code-signing
GitHub action for updating the xcodeproj file for manual code-signing.

## Usage
Add the following step to your GitHub Actions workflow:

```yaml
- name: 🔑 Update the xcodeproj file for manual code-signing
  uses: antigua-mobile/ios_xcodeproj_manual_signing@v1.0
  with:
    provisioning_profile_path: '...'
```