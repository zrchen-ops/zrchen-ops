# Zirui Chen

Sophomore at Guangdong University of Technology, focused on practical AI applications and agents.

I build useful product experiences by connecting AI models, retrieval, and application workflows.

## Selected Projects

### [Jiheng World](https://github.com/Lzhtommy/Jiheng/tree/codex/jiheng-mvp)

**Team project · Contributor — Interactive Industry Research Module**

My code contributions to the team's interactive company and industry-chain research experience:

- Built the pixel World entry layer in `world-entry.js`: responsive company layouts, CSS character movement, building selection, company cards, and event-based transitions into the investigation flow.
- Added `world-state.js` save migration from v1 to v2, separating World and scenario state while keeping legacy scenario fields compatible with existing gameplay code.
- Implemented evidence-gated negotiation in `procurement-journey.html`: offers depend on clues from the inventory ledger, quarterly contract, and production schedule board.
- Built the cell-city investigation around three evidence cards: material-cost changes, production efficiency, and demand-versus-price signals. Players connect the cards before the analysis and next chapter unlock.
- Added Node tests for clue/offer requirements and evidence-combination progression; synchronized the web assets with the Flutter app.

Implementation: [Pixel World and workshop layer](https://github.com/Lzhtommy/Jiheng/commit/501e55671a07f65212b6b81872d8a2e508f5555b) · [Cell-city evidence gameplay](https://github.com/Lzhtommy/Jiheng/commit/8ab7230a126244dd6934eaee7c3c9935ffdad2e1)

These contributions were committed from my other GitHub account, [@dream-oc](https://github.com/dream-oc).

### [PlaudStudy](https://github.com/zrchen-ops/plaudstudy)

An AI study workflow for traceable, timestamp-grounded answers from recorded audio.

- Pipeline: **ASR → timestamped chunks → embeddings → Qdrant → RAG**
- FastAPI backend with faster-whisper and BGE embeddings
- Answers linked to source timestamps for easier verification
- Multimodal workflow experiments

## Tech Stack

Python · JavaScript · FastAPI · Flutter/Dart · faster-whisper · BGE · Qdrant · RAG · Multimodal AI · Automated Testing

## Current Focus

**AI Agents · Practical AI Applications · Retrieval and Grounding · Multimodal Workflows**
