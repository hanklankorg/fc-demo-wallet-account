# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.11] - 2026-11-15

### Added

- Add HSM client id endpoints for accounts
- Add missing crv (#62)
- Add codeowners (#58)
- Add request-response logging (#55)
- Add sonarqube analysis (#52)
- Add more tests for increased coverage (#49)
- Add test tools
- Add security envelope and wallet key to database (#37)
- Add ecosystem integration test workflow
- Add no-op version control linter
- Add spotbugs exclude filter to suppress EI_EXPOSE_REP and EI_EXPOSE_REP2 errors
- Add spotbugs exclude filter to suppress NM_METHOD_NAMING_CONVENTION errors
- Add bare bone spring boot application

### Changed

- Use the lab's Forge CI layer
- Name the snapshot and release flows as the other projects do
- Name the snapshot flow release-snapshot-workflow.yml
- Report SAST findings without failing the pull request
- Migrate workflows to forge-ci
- Pin postgres docker tag to ca0bd48 (#97)
- Stop storing wallet key and personal data (#91)
- Update java non-major (#94)
- Update diggsweden/wallet-ecosystem digest to 002f8a4 (#96)
- Update diggsweden/wallet-ecosystem digest to 726b7d0 (#92)
- Update diggsweden/wallet-ecosystem digest to 8cfebb0 (#88)
- Update java non-major (#89)
- Fix/renovate cleanup (#86)
- Update docker.io/library/eclipse-temurin:25-jdk-alpine docker digest to 541729c (#25)
- Update cgr.dev/chainguard/jre:latest docker digest to df582a7 (#21)
- Update org.apache.tomcat.embed:tomcat-embed-core to v11.0.25 [security] (#82)
- Update java non-major (#80)
- Fix/renovate config (#85)
- Error logging improvements (#81)
- Update github actions (#79)
- Update dependency prettier to v3.9.6 (#78)
- Update java major to v53 (#28)
- Api-spec improvements (#73)
- Handle unique kid in db (#72)
- Log request and response separately (#69)
- Merge pull request #63 from diggsweden/fix/account-overwriting
- Merge pull request #59 from diggsweden/feat/hsm-client-id
- Bump rest-api-linter to v2.0.0 (#61)
- Merge pull request #57 from diggsweden/chore/remove-sonarqube
- Problem response (#56)
- Pin actions to commit sha (#53)
- Merge pull request #50 from diggsweden/build/upgrade-spring-boot-4.0.6
- Upgrade spring-boot to 4.0.6 to fix CVE-2026-40976
- Bump reusable-ci to v2.8.2
- Bump gommitlint to 0.9.10, switch rumdl from ubi to aqua
- Bump reusable-ci to v2.7.9
- Merge pull request #43 from diggsweden/fix/use-main-version-of-reusable-integration
- Feat/add key operations with api (#40)
- Merge pull request #41 from diggsweden/chore/upgrade-java-25
- Upgrade to java 25
- Merge pull request #39 from diggsweden/chore/bump-reusable-integration-workflow
- Bump reusable integration workflow
- Merge pull request #38 from diggsweden/chore/bump-reusable-integration-workflow
- Merge pull request #35 from diggsweden/feature/ecosystem-integration-test
- Use gommitlint instead of conform
- Update reusable-ci to v2.7.3
- Merge pull request #33 from diggsweden/fix/use-gommitlint
- Use gommitlint
- Merge pull request #32 from diggsweden/build/fail-on-dirty-working-tree
- Enable version control linter
- Merge pull request #30 from diggsweden/chore/bump-reusable-ci-to-v2.6.1
- Bump workflows to use reusable-ci v2.6.1
- Merge pull request #31 from diggsweden/fix/bump-hadolint-to-v2.14.0
- Update actions/setup-java action to v5.2.0 (#27)
- Update java non-major (#26)
- Update dependency org.assertj:assertj-core to v3.27.7 [security] (#24)
- Update dependency prettier to v3.8.1 (#23)
- Update actions/checkout action to v6.0.2 (#22)
- Merge pull request #15 from diggsweden/renovate/lock-file-maintenance
- Lock file maintenance
- Merge pull request #7 from diggsweden/renovate/cgr.dev-chainguard-jre-latest
- Update cgr.dev/chainguard/jre:latest docker digest to f7b0d54
- Update dependency prettier to v3.8.0 (#20)
- Update dependency com.nimbusds:nimbus-jose-jwt to v10.7 (#19)
- Update docker.io/library/eclipse-temurin docker tag to v25
- Update actions/checkout action to v6
- Update actions/setup-java action to v5
- Update minor versions in pom
- Update dependency prettier to v3.7.4
- Adapt to spring boot 4
- Update java major
- Update github actions (#8)
- Use reuseable ci 2.6.0
- Change devbase-justkit name, improve dev doc
- Update justfile and reuseable-ci
- Refactor dto class and db-mappings
- Happy case code and test
- Bootstrap non-code files
- Initial commit

### Fixed

- Leave the ecosystem integration workflow out of the trial
- Fix list indentation in DEVELOPMENT.md
- Example json syntax (#84)
- Api spec and log fix (#76)
- Api component test improvements (#65)
- Account api test improvements (#64)
- Check account uniqueness by device key kid
- Fix commit sha (#54)
- Email and personal identity number are now optional (#51)
- Get blob within transaction (#48)
- Test coverage improvement (#46)
- Map string to blob (#45)
- Handle walletKey and deviceKey similarly (#44)
- Use main version of reusable integration script
- Bump reusable integration workflow
- Bump hadolint to v2.14.0
- Copy of ObjectMapper to avoid EI_EXPOSE_REP2 error
- Correct a few lint errors
- Allow null telephonenumber and longer kid
- Fix license and megalinter

### Removed

- Remove personal account optionals in api (#99)
- Remove the optional datatype for generated models (#98)
- Remove mise paranoid setting (#93)
- Remove old api (#66)
- Remove sonarqube integration
- Remove now deprecated pmd rule
- Remove setters from PublicKeyEntity and remove exclude filter for AccountEntity
- Remove duplicate PMD rule



<!-- generated by git-cliff -->
