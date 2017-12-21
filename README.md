# Disability Ontology
This is a repository for the CCSO project's disability ontology. 

Recent updates: 
1. Published vocabulary with prefixes but without imports
2. Incorporated classmates' ontologies related to employment. 

These ontologies allowed me to include more ways to describe a "person," such as "student," "prisoner," and "employee." 
Previously, my ontology was limited to "person with disability" as a "person." While pivotal to my ontology, a "person" is more than their disabilities. "student," "prisoner," and "employee." 
 
Additionally, these ontologies allowed me to expand upon forms of schooling or employment. In the past, I had a class "employment" which mainly conveyed "current employment." Now, I have assertions and inferences for employment-related concepts such as "self-employment," "retired," and "not employed."  

Furthermore, I included the class "employment opportunity" but decided to have it as a sister class and not a sub-class of "employment. The rationale behind this is that it should be on the same level as "employment" and and other classes such as "skill" because an potential opportunity is based upon many more factors than just previous/current employment status. 

Doing so allows for important assertions (and the ones that I was after when first dreaming up this ontology) for employment opportunity like: 
is_able_to only 'Fine hand use' and is_able_to only 'Maintain a sitting position' and (has_skill some 'Technical Skill' or Had_Previous_Education_Field some Education)

4. Used one or more of the Org Relationship terms

Under "employment" I included the sub-class "work relationship," which then included "current employment, "retired," "unemployed," etc. Additionally, I included the "organization" class and its subsequent "employer," "school" and "employing organization" sub-classes. 

5. Created a test vocabulary that imports vocabularies you need to test the inferences

When doing this, several more terms that I didn't need for my visualization of salient information appeared. Therefore, I put these under the class "unwanted terms." This was one of my most prevelant limitations. 

6. Inferences work, because imported vocabularies are logically consistent.
