Program excepts input file name as one of the arguments while running.

Input: The input consists of several sections.  The beginning of each section is marked by a line starting: “# Section:”
```
Section 1: A weighted bi-directional graph describing the conveyor system.
Format: <Node 1> <Node 2> <travel_time>

Section 2: Departure list Format:
<flight_id> <flight_gate> <destination> <flight_time>
Section 3: Bag list Format:
<bag_number> <entry_point> <flight_id>
```

Output: The optimized route for each bag
```
<Bag_Number> <source> <destination> : <total_travel_time>
```

The output should be in the same order as the Bag list section of the input.# BaggageSystem

