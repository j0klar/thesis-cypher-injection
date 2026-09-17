## Abstract

Injection attacks have been a long-standing and omnipresent threat to database systems ever
since their inception. While most often targeting traditional relational databases and SQL, the
attack paradigm of injection has over time been successfully adapted to also take aim at NoSQL
databases and their query languages. This thesis investigates the topic of Cypher Injection,
that is, the concept of classic SQL injection adjusted to target the Neo4j graph database and
its associated Cypher language. Existing SQL Injection Attack (SQLIA) taxonomies will be
examined to assess the feasibility of transferring various types of SQLIAs to Neo4j and Cypher,
as well as to identify the adaptations required. For this purpose, this thesis will more closely
examine a number of frequently used yet loosely defined terms related to the construction
and execution of database queries, such as static, dynamic, and parameterized. Dynamic queries
in particular will be given special attention, as they make up the most problematic class of
queries with regard to injection attacks. Consequently, a variety of different approaches aimed
at mitigating the risks posed by dynamic query construction as well as the wide-ranging
implications of these risks for database security will be evaluated in depth.

## Research Question

Which countermeasures can be applied to secure dynamically constructed Cypher queries
in Neo4j against injection attacks, especially where parameterization is not possible?
