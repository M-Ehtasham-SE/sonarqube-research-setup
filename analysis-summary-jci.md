\# SonarQube Analysis Summary — Apache Commons JCI



\## Repository Information

| Field | Value |

|-------|-------|

| Repository | Apache Commons JCI |

| Repository URL | https://github.com/apache/commons-jci |

| Student | 24F-3098 |

| Team | (apni team) |

| Default Branch | master |

| Checked-out Commit | 42f037651be8ce83423a9ad14645610efaf23b92 |

| Commit Date | 2025-12-29 |



\## Build Information

| Field | Value |

|-------|-------|

| Build System | Maven |

| Build Command | `mvn clean verify -DskipTests -Dspdx.skip=true` |

| Build Status | ✅ Success |



\## SonarQube Analysis

| Field | Value |

|-------|-------|

| SonarQube Version | v26.7.0.124771 |

| SonarQube Project Key | team-24f-3098-jci |

| Analysis Status | ✅ Success |



\## 4 Code Smells Results



\### 1. Flag Argument

| Field | Value |

|-------|-------|

| Rule Used | Not available in default profile |

| Rule Active | ❌ No |

| Findings Count | Not analysed — rule unavailable |



\### 2. Null Check

| Field | Value |

|-------|-------|

| Rule Used | `squid:S2259` |

| Rule Active | ✅ Yes |

| Findings Count | 2 |



\### 3. Complicated Boolean Expression

| Field | Value |

|-------|-------|

| Rule Used | `squid:S1067` |

| Rule Active | ✅ Yes |

| Threshold | 3 |

| Findings Count | 10 |



\### 4. Conditional Complexity

| Field | Value |

|-------|-------|

| Rule Used | `squid:S134` |

| Rule Active | ✅ Yes |

| Threshold | 3 |

| Findings Count | 13 |



\## Problems Encountered

\- SPDX license timeout during build — resolved using `-Dspdx.skip=true`

\- Maven path issue — resolved after setting correct PATH

\- SonarQube plugin missing in POM — added manually



\## Solutions Attempted

\- Added `-Dspdx.skip=true` flag for build

\- Added SonarQube plugin to POM

