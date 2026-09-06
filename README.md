# \# Intune Management

# 

# Infrastructure-as-Code and automation repository for Microsoft Intune.

# 

# \## Purpose

# 

# This repository manages:

# 

# \- Microsoft Intune policies

# \- Configuration profiles

# \- Compliance policies

# \- Endpoint security policies

# \- PowerShell scripts

# \- Remediation scripts

# \- Win32 applications

# \- Microsoft Graph automation

# \- Infrastructure configuration

# \- Automated testing

# \- CI/CD deployment

# 

# \## Environments

# 

# | Environment | Purpose |

# |---|---|

# | DEV | Development and testing |

# | TEST | Validation |

# | PROD | Production |

# 

# \## Repository Structure

# 

# \- `apps/` - Intune applications

# \- `policies/` - Intune policies

# \- `scripts/` - PowerShell automation

# \- `graph/` - Microsoft Graph automation

# \- `tests/` - Automated tests

# \- `templates/` - Reusable templates

# \- `docs/` - Documentation

# \- `infrastructure/` - Terraform/Bicep

# \- `.github/` - CI/CD workflows

# 

# \## Deployment Flow

# 

# Feature branch

# → Pull Request

# → Validation

# → Code Review

# → Merge

# → Test Deployment

# → Approval

# → Production Deployment

# 

# \## Security

# 

# No credentials, secrets, tokens, certificates or generated `.intunewin`

# packages should be committed to this repository.

# 

# \## Ownership

# 

# Intune Engineering Team

