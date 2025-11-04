# Sandbox

Individual developer playgrounds for experimentation and learning.

## Purpose

The sandbox is your personal space to:
- Try new technologies and frameworks
- Experiment with different patterns and architectures
- Learn and break things safely
- Prototype ideas before implementing them in production

## Structure

Each developer has their own protected directory:

```
sandbox/
├── john_doe/
├── jane_smith/
└── yourname_lastname/
```

## Getting Started

### 1. Create Your Sandbox

```bash
mkdir -p sandbox/yourname_lastname
cd sandbox/yourname_lastname
```

### 2. Add Yourself to CODEOWNERS

Edit `.github/CODEOWNERS` and add:

```
/sandbox/yourname_lastname/ @your-github-username
```

### 3. Start Experimenting

Create whatever structure works for you:

```
sandbox/yourname_lastname/
├── experiment-1-minimal-api/
├── experiment-2-grpc/
├── learning-ddd/
└── prototype-feature-x/
```

## Best Practices

### Documentation
- Add a README to each experiment explaining what you're trying
- Document interesting findings and lessons learned
- Share "aha moments" with the team

### Organization
- Use descriptive folder names
- Clean up old experiments periodically
- Archive successful experiments or move them to `gists/`

### Collaboration
- Your sandbox is protected, but you can still share!
- Give demos of interesting work to the team
- Move reusable code to `gists/` for others to use

## Examples of What to Try

### Learning New Technologies
```
sandbox/yourname_lastname/learning-dapr/
├── README.md
├── pubsub-example/
└── state-management/
```

### Prototyping Features
```
sandbox/yourname_lastname/prototype-auth-service/
├── README.md
├── src/
└── tests/
```

### Testing Architectures
```
sandbox/yourname_lastname/clean-architecture-experiment/
├── README.md
└── notes.md
```

## Freedom to Explore

Your sandbox is yours:
- No approval needed for changes in your space
- Break things without worry
- Try unconventional approaches
- Learn at your own pace

## Graduating from Sandbox

When an experiment is successful:
1. **Reusable code** → Move to `/gists/`
2. **Patterns & practices** → Document in `/standards/`
3. **Production-ready** → Move to appropriate project

## Tips

- Don't overthink it - just start experimenting!
- It's okay if experiments fail - that's how we learn
- Share your learnings in team meetings
- Help others by reviewing their experiments
- Keep a learning journal in your sandbox

## Questions?

Ask any team member for guidance or share what you're working on in team chat!
