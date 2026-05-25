## Phase 2: Data Handling & JSON Literacy
**Project:** The Contact Synthesizer

**Objective:** Master JSON dot notation to dynamically reshape data payloads.

**Technical Execution:**
* **Input Schema:** The workflow ingests tabular data formatted as JSON containing `first_name` and `last_name`.
* **The Expression:** `{{ $json.first_name }} {{ $json.last_name }}`
* **Data Transformation:** The pipeline utilizes an Edit Fields (Set) node to parse the incoming JSON, extract the separate string values via dot notation, and synthesize them into a single, newly generated `full_name` key-value pair. This standardizes the payload for external systems that do not accept fragmented name fields.