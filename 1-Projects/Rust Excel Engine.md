# Rust Excel Engine

### Project Mapping
- [ ] Create a diagram of project flow  [priority:: highest]  [created:: 2024-10-16]  [start:: 2024-10-16]  [due:: 2024-10-16]
- [ ] Figure out how the mapping fits with Frankie's initial push  [priority:: highest]  [created:: 2024-10-16]  [scheduled:: 2024-10-16]  [due:: 2024-10-16]
- [ ] Figure out how we're supposed to be using Pest  [priority:: high]  [created:: 2024-10-16]
	- [ ] When should we use the pest alphabet?
	- [ ] Do we create a parser class using the pest library?
- [ ] Review required libraries  [priority:: high]  [created:: 2024-10-16]

### Flow?
1. Read user input using calamarine?
2. Logical table analysis?
	1. Figure out which parts of the worksheet are logical?
	2. Translate each cell into a "Node" with a parsable string value?
3. Parse excel into rust using pest

### Unknowns
- Pest's place in the project
- Starting input
- Ending output
- How to build the dependency map