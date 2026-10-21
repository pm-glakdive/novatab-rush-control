# NovaTab · Rush Control

A high-fidelity, interactive design study for a 1024 × 768 restaurant touchscreen.

**Open:** `index.html` directly, or use the GitHub Pages link. No install or account required. All interactions are local simulations.

**Main flow:** Review rush incident → evidence → relief plan → choose actions → approve → execution → partial execution → check status → confirmation → later review → reversal → recovery receipt.

**Branches:** stock uncertainty and verified count; manager disagreement and revised recommendation; manual recovery when channel status remains unavailable. The bottom screen navigator provides direct access to the 13 core and edge states; arrow keys also browse them. Restart resets the scenario. Use the on-screen controls to experience the workflow.

**Editable design files:** `design-files/` contains 1024 × 768 SVGs with editable text and vector shapes. `index.html`, `style.css`, and `app.js` are the editable source. `screens/` contains PNG references. `tokens.json` captures the visual palette and touch sizing. Inter is bundled under its SIL Open Font License.

**Brief design notes**
- A manager on the move sees one prioritized rush incident; related signals are grouped.
- AI interprets and proposes. The manager approves exact scope. Staff changes remain a lead decision.
- Selection, approval, execution, acknowledgement and recovery are distinct states.
- A timeout means unknown outcome: verify before retrying. Manual verification is labeled separately.
- A reversal affects future settings; accepted orders and sent tasks cannot be recalled.
- A stale stock count requires physical verification before a menu decision.

**Scenario integrity:** 47 orders, prep rising from 6 to 11 minutes, rising delivery demand, two absences, waiting guests and low stock come from the exercise. The restaurant, person, item name, station breakdown, order examples, counts, delivery estimates, timings and later outcomes are illustrative assumptions. No connected systems, real orders, performance promises or live operational claims.

The cached prior conversation contained the user's framing and approval/control concerns but not the previous assistant's Rush Control draft. This study continues that framing without claiming access to the missing draft.
