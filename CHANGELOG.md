# 2025.11.1

- Fix regression in frame editor (!222, !223).

# 2025.11.0

- Address bug that prevented raw Ergo from being displayed in some cases (!220).

- Improve case handling for predicate/rule names (!217).

- Improve handling of knowledge base information. Addresses bugs relating to
  various sequences of adding and removing bouts, background, and other ergo
  elements (!215, !216, !219).

- Re-prompt LLM for query-extraction when parsing fails (!214).

# 2025.10.3

- Fixed bug relating to query binding results.

- Fixed rule naming bug.

# 2025.10.2

- Add guidance field allowing users to provide directions to the LM in addition
  to the natural language describing the rule content itself (!210).

- Add button to clear filter/search text (!208).

- Add link from UI to documentation (!201).

- Catch rate-limit error from LM and fall back to query without background
  (!196).

- Display bindings that result from running queries (!198).

- Use LM to automatically select candidate frame type when showing frame editor
  (!186).

- Add link predicates to foreground knowledge (!194).

- Fixed deserialization bugs (!191, !204).

# 2025.10.1

- Initial version exposed publicly for APL T&E team.
