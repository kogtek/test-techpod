# TechPod .NET Monorepo

A monorepo for collaborative learning, experimentation, and shared knowledge within the TechPod team.

## Repository Structure

```
techpod-dotnet/
├── sandbox/              # Individual developer playgrounds
├── standards/            # Code standards and best practices
├── docker/               # Container configurations
├── testing/              # Testing frameworks and utilities
├── load_testing/         # Performance testing scripts
├── security/             # Security configurations and tools
├── gists/                # Shared code snippets and implementations
└── .github/
    └── CODEOWNERS        # Access control and code review requirements
```

## Purpose

This repository serves multiple purposes:

1. **Learning & Experimentation**: Use the `sandbox/` area to try new technologies and patterns
2. **Knowledge Sharing**: Contribute to `gists/` with reusable implementations
3. **Standards Governance**: Maintain team standards through protected directories
4. **Collaborative Development**: Work together while maintaining code quality through CODEOWNERS


### Protected Areas (Ambassador-owned)
These require approval from designated domain ambassadors:

- **`/standards/`** - Code standards, architectural guidelines, best practices
- **`/docker/`** - Container configurations, Dockerfiles, compose files
- **`/testing/`** - Test frameworks, shared test helpers, testing utilities
- **`/load_testing/`** - Performance testing scripts and configurations
- **`/security/`** - Security policies, configurations, scanning tools


### Shared Areas
- **`/gists/`** - Protected by all team members
  - Small reusable implementations
  - Examples: Auth/Authz, AWS integrations, utility functions
  - Any team member can review and approve


## 📝 Contributing

### To Your Sandbox
1. Work freely in your own sandbox area
2. No approval needed for your own space
3. Document your experiments for future reference

### To Protected Areas
1. Create a feature branch
2. Make your changes
3. Submit a PR
4. Get approval from the designated ambassador
5. Merge once approved

### To Gists
1. Ensure your implementation is:
   - Well-documented
   - Reusable
   - Tested (if applicable)
2. Submit a PR
3. Get approval from any team member
4. Merge once approved
