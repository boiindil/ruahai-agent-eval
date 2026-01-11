# ruahAI Agent Eval

## What this is
`ruahai-agent-eval` is a **black-box evaluation agent** distributed as a container image.
It produces **reduced, non-commercial evaluation output only**.

The purpose is to:
- demonstrate capability and structure
- allow technical and governance-oriented evaluation
- define the interface required for licensed, full-grade output

## What this is NOT
- Not open source
- Not a free production tool
- Not legal, regulatory, or operational advice
- Not a full deliverable generator

## Container Image
```
ghcr.io/boiindil/ruahai-agent-eval:latest
```

## Usage (Evaluation Mode Only)
```
echo "Your request here" | docker run -i --rm ghcr.io/boiindil/ruahai-agent-eval:latest
```

The output is intentionally limited and **does not include licensed deliverables**.

## Commercial Use
Any commercial, client-facing, or revenue-generating use of outputs
**requires an explicit Output License**.

See: `OUTPUT_LICENSE.md`

## Contact
- Email: brueckner@bw-ruah.de
- Website: https://bw-ruah.de

Exclusivity, custom agents, or full licensed outputs are handled **off-platform**.
