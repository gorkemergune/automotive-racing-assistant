# TASKS.md

# Automotive Racing Assistant

## Phase 0 — Environment

- [x] Inspect original repository
- [x] Inspect `ollama_asistan/chat.py`
- [x] Inspect `ollama_asistan/tools.py`
- [x] Inspect `ollama_asistan/ollama_client.py`
- [x] Inspect `ollama_asistan/medical_rag.py`
- [x] Verify Python
- [x] Verify Ollama
- [x] Pull `qwen2.5:7b-instruct` (already present locally)
- [ ] Run original template
- [x] Verify existing tool-calling flow

---

## Phase 1 — Automotive Scenario

- [x] Rename assistant identity
- [x] Update system prompt
- [x] Set Qwen2.5 7B
- [x] Remove medical terminology
- [x] Create `race_data.py`
- [x] Add vehicle component data
- [x] Add racing regulation data

---

## Phase 2 — Tools

### Internet

- [x] Preserve `internet_search`
- [x] Verify search functionality
- [ ] Test search failure

### Weather

- [x] Implement/verify `get_weather`
- [x] Test location handling
- [ ] Test failure handling

### Vehicle

- [x] Implement `check_part_status`
- [x] Add brake pads
- [x] Add tires
- [x] Add engine oil
- [x] Add battery
- [x] Add brake discs
- [x] Handle unknown components

### Regulations

- [x] Implement `get_race_regulations`
- [x] Add brakes
- [x] Add tires
- [x] Add safety
- [x] Add electrical
- [x] Add driver
- [x] Add technical inspection
- [x] Handle unknown topics

---

## Phase 3 — System Prompt

- [x] Define assistant role
- [x] Define scenario
- [x] Define tools
- [x] Define tool-selection rules
- [x] Define when not to use tools
- [x] Define tool result handling
- [x] Add hallucination prevention
- [x] Define mock-data limitations
- [x] Define multi-tool behavior
- [ ] Add few-shot examples (evaluated and INTENTIONALLY OMITTED: call-syntax examples
      caused text-leakage on qwen2.5:7b-instruct — see docs/prompt_design.md)
- [x] Test prompt with Qwen2.5 7B
- [x] Optimize failed cases

---

## Phase 4 — Testing

- [ ] Direct answer
- [ ] Weather
- [ ] Part status
- [ ] Regulations
- [ ] Internet search
- [ ] Multi-tool
- [ ] Unknown information
- [ ] Invalid arguments
- [ ] Tool failure
- [ ] Maximum tool rounds

---

## Phase 5 — Reliability

- [ ] Ollama connection failure
- [ ] Malformed tool call
- [ ] Unknown tool
- [ ] Missing arguments
- [ ] Invalid arguments
- [ ] Tool exception
- [ ] Search failure
- [ ] Weather failure
- [ ] Unknown component
- [ ] Unknown regulation
- [ ] Infinite-loop protection

---

## Phase 6 — Documentation

- [ ] Project overview
- [ ] Assignment goals
- [ ] Architecture
- [ ] Technologies
- [ ] Installation
- [ ] Ollama setup
- [ ] Model setup
- [ ] Usage
- [ ] Tool documentation
- [ ] System prompt strategy
- [ ] Real conversation #1
- [ ] Real conversation #2
- [ ] Real conversation #3
- [ ] Real conversation #4
- [ ] Multi-tool conversation
- [ ] Tool call logs
- [ ] Testing results
- [ ] Limitations
- [ ] Future improvements
- [ ] Project structure

---

## Phase 7 — Final Submission

- [ ] Clean Git status
- [ ] Remove secrets
- [ ] Verify `.gitignore`
- [ ] Run final tests
- [ ] Verify README commands
- [ ] Create final commit
- [ ] Push GitHub repository
- [ ] Create Hugging Face repository
- [ ] Push project to Hugging Face
- [ ] Verify both repositories
- [ ] Prepare submission links
