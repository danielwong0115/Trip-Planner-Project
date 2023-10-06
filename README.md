# Trip-Planner-Project

### Preamble:
This project was created in August 2023. It runs on top of the Racket environment using the DSSL2 (Data Structures Student Language 2) language.

### Purpose:
This is a project that translates user location information and stores it into a simplified graph model. The graph would then be ingested into shortest path and sorting algorithms to extract map information relevant to the user's queries.

### TripPlanner Class
The `TripPlanner` class consists of 6 classes: `category_dict`, `name_dict`, `pos_dict`, `vtx_dict`, `pos_to_poi` and `WUGraph`. `WUGraph` was a weighted, undirected graph implemented using an adjacency matrix to allow for efficient searching of edges between destinations. The other fields are dictionaries to store and translate between user and graph data such as mapping between destination positions to graph vertices in `pos_dict`. The initialzer also has three methods: `locate_all`, `plan_route`, and `find_nearby`.

### Steps for Running
1. Install DrRacket version 8.9 from https://racket-lang.org/.
2. Clone the repository.
3. Open `planner.rkt` inside DrRacket and click the run button on the top right corner
