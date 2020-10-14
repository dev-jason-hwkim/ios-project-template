# iOS Project Template

# XCodeGen

## Project.yml

XcodeGen Template File

# Fastlane

Fastlane Template File (AppFile, MatchFile, FastFile, PluginFile)

## beta.yml, release.yml

GitHub Action Template Files

### Secrets Values

#### Common Secrets
- GH_TOKEN: GitHub Token
- MATCH_PASSWORD: Match password
- MATCH_REPO: Match Repository
  <br>

#### Beta Secrets (beta.yml)
- FIREBASE_APP_ID: Firebase App ID (Using Firebase Distribution)
- FIREBASE_TOKEN: Fireabase cli token (Using Firebase Distribution)
<br>

#### Release Secrets (release.yml)
- APPLE_ACCOUNT: Apple Account
- FASTLANE_APPLE_APPLICATION_SPECIFIC_PASSWORD: Application Password
- FASTLANE_SESSION: fastlane spaceauth -u user@example.org
- ITC_TEAM_ID: Spacership team ID
- TEAM_ID: Developer Membership ID


