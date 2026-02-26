# Network-Analysis-Epstein

Primary Research Question

"How does the evolution of Jeffrey Epstein’s travel patterns and communication network reveal the changing structure of his social influence and legal exposure over time?"

This question is effective because it forces you to connect the Flights (physical movement) with the Emails (social movement) and Documents (legal consequences), rather than just plotting points on a map.

Sub-Questions (Assigned by Group Role)

To make the project manageable, assign one sub-question to each group member. This ensures everyone has a specific dataset to clean and visualize.

1. The Network Analyst (Social Network Analysis)

· Focus: epstein-emails.csv & epstein-flights.csv (Co-travelers)

· Sub-Question: "Who are the central 'brokers' in the Epstein network that bridge unconnected groups (e.g., connecting scientists to politicians), and does this central circle change after his 2008 conviction?"

· Visualization: Network graph (Nodes = People, Edges = Emails/Flights). Size nodes by "Betweenness Centrality" to show influence.

2. The Geospatial Analyst (Spatiotemporal Analysis)

· Focus: epstein-flights.csv

· Sub-Question: "How did the frequency and diversity of flight destinations shift during periods of high legal scrutiny, and are there 'safe haven' locations that appear repeatedly during these times?"

· Visualization: Animated flight route map over time, or a heatmap of destinations comparing "Pre-2008" vs. "Post-2008".

3. The Content Analyst (Text Mining)

· Focus: epstein-documents.csv & epstein-emails.csv (Body text)

· Sub-Question: "What are the dominant topics and keywords in the legal documents and correspondence, and do specific keywords (e.g., 'deposition', 'settlement') correlate with spikes in travel or email activity?"

· Visualization: Word clouds, topic modeling (LDA) clusters, or a timeline of document release dates overlaid with flight frequency.

4. The Profiler (Categorical Analysis)

· Focus: epstein-persons.csv & epstein-flights.csv

· Sub-Question: "What is the discrepancy between the 'aspirational' network (names in the Black Book) and the 'actual' network (people who flew on the plane), and which categories of people (e.g., Politicians vs. Associates) remained loyal the longest?"

· Visualization: Venn diagram (Black Book vs. Flight Logs) and a stacked bar chart showing the category breakdown of top associates. 