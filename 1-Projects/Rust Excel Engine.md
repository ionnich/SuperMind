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

### Aider Flow?
 1 Read input (calamarine)
    • Load the Excel file data
 2 Logical table analysis
    • Identify relevant cells and ranges
    • Create initial "Node" structures for cells
 3 Parse formulas (Pest)
    • For each cell with a formula:
       • Use Pest to parse the formula into a Rust-friendly
         structure
       • This step gives you the "ingredients" of each
         formula
 4 Build dependency graph
    • Iterate through parsed formulas
    • For each formula:
       • Identify cells it depends on
       • Add edges in the graph from dependencies to the
         current cell
    • This step creates a DirectedGraph or similar structure
 5 Compile and evaluate
    • Use the dependency graph to determine evaluation order
    • Compile formulas into executable Rust code
    • Evaluate cells following the graph order
### Unknowns
- Pest's place in the project
- Starting input
- Ending output
- How to build the dependency map