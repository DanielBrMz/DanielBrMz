### Hey, I'm Daniel 🐸

I lead the technical direction of systems end to end: cloud backends, ML models and the products on top of them. Usually with too many terminals open.

```python
from dataclasses import dataclass, field


@dataclass(frozen=True)
class Engineer:
    name: str = "Daniel Barreras"
    role: str = "Lead software engineer · cloud, ML, full stack"
    what_i_do: tuple[str, ...] = (
        "set technical direction and own architecture across services",
        "lead migrations that span teams and partner companies",
        "turn research models into production systems",
        "mentor engineers and own releases and production health",
    )
    experience: dict[str, str] = field(default_factory=lambda: {
        "Sidepocket": "tech lead, architecture of 8 Python services on AWS",
        "Capital One": "lead software engineer, AWS serverless backends",
        "Oracle": "software engineer, OCI GPU infrastructure",
        "Harvard Medical School / BCH": "research engineer, fetal MRI deep learning",
    })
    stack: tuple[str, ...] = ("Python", "TypeScript", "Java", "Go", "AWS",
                              "PostgreSQL", "PyTorch", "Next.js")
    agents: tuple[str, ...] = ("Claude Code", "MCP")
    shipped: dict[str, str] = field(default_factory=lambda: {
        "Phoenix Eye": "wildfire detection from satellite imagery (NASA Space Apps global finalist team)",
        "FetEnhNet": "deep learning for fetal MRI enhancement, paper on the way",
    })
    ask_me_about: tuple[str, ...] = ("system design", "AWS", "migrations",
                                     "PyTorch", "LLM agents")


daniel = Engineer()
```

**Things I've made**

| Project | |
|---|---|
| [Phoenix](https://github.com/DanielBrMz/Phoenix) | Spotting wildfires from space with satellite imagery and a 3D map. NASA Space Apps global finalist team, Prototypes for Humanity 2024 in Dubai. |
| [vanguard-mri-harmonization](https://github.com/DanielBrMz/vanguard-mri-harmonization) | Making MRI scans from different hospitals and scanners look like they came from the same machine. |
| [hopfield-network](https://github.com/DanielBrMz/hopfield-network) | A neural network that remembers things, built from scratch. |
| [red-neuronal](https://github.com/DanielBrMz/red-neuronal) | Another neural net from scratch, because doing backprop by hand is a rite of passage. |

Say hi on [LinkedIn](https://linkedin.com/in/danielbrmz) 👋
