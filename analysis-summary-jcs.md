# SonarQube Analysis Summary — Apache Commons JCS

## Repository Information
| Field | Value |
|-------|-------|
| Repository | Apache Commons JCS |
| Repository URL | https://github.com/apache/commons-jcs |
| Student | 24F-3098 (Ehtasham) |
| Team | Ehtasham |
| Default Branch | master |
| Checked-out Commit | ad44e7b97ac7d6b7462088c22ed29acfc3c38b31 |
| Commit Date | 2025-12-31 |

## Build Information
| Field | Value |
|-------|-------|
| Build System | Maven |
| Build Command | `mvn clean verify -DskipTests -Dspdx.skip=true` |
| Build Status | ✅ Success |

## SonarQube Analysis
| Field | Value |
|-------|-------|
| SonarQube Version | v26.7.0.124771 |
| SonarQube Project Key | team-24f-3098-jcs |
| Analysis Status | ✅ Success |

## 4 Code Smells Results

### 1. Flag Argument
| Field | Value |
|-------|-------|
| Rule Used | Not available in default profile |
| Rule Active | ❌ No |
| Findings Count | Not analysed — rule unavailable |

### 2. Null Check
| Field | Value |
|-------|-------|
| Rule Used | `squid:S2259` |
| Rule Active | ✅ Yes |
| Findings Count | 2 |

### 3. Complicated Boolean Expression
| Field | Value |
|-------|-------|
| Rule Used | `squid:S1067` |
| Rule Active | ✅ Yes |
| Threshold | 3 |
| Findings Count | 10 |

### 4. Conditional Complexity
| Field | Value |
|-------|-------|
| Rule Used | `squid:S134` |
| Rule Active | ✅ Yes |
| Threshold | 3 |
| Findings Count | 13 |

## Problems Encountered
- SPDX license timeout during build — resolved using `-Dspdx.skip=true`
- Maven path issue — resolved after setting correct PATH
- SonarQube plugin missing in POM — added manually
- Git clone large repo issue — resolved using shallow clone with `--depth=1` and `--depth=500`

## Solutions Attempted
- Added `-Dspdx.skip=true` flag for build
- Added SonarQube plugin to POM
- Used shallow clone with `--depth=1` and `--depth=500`

## Observations
- JCI and JCS both are Apache Commons repositories
- Both repositories have similar code patterns and coding standards
- Both commits are from the same author (Gary Gregory)
- SonarQube rules applied with default thresholds
- Findings counts are identical to JCI
