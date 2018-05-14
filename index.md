#MCP
To facilitate communication among stakeholders, software security requirements are typically written in natural language and capture both positive requirements (i.e., what the system is supposed to do to ensure security) and negative requirements (i.e., undesirable behavior undermining security).

Misuse Case Programming (MCP) is an approach that automatically generates security test cases from misuse case specifications (i.e., use case specifications capturing the behavior of malicious users).

MCP tackles the problem of automatically generating executable security test cases from security requirements in natural language (NL). More precisely, since existing approaches for the generation of test cases from NL requirements verify only positive requirements, we focus on the problem of generating test cases from negative requirements.
 
MCP relies on natural language processing techniques to extract the concepts (e.g., inputs and activities) appearing in requirements specifications and generates executable test cases by matching the extracted concepts to the members of a provided test driver API. MCP has been evaluated in an industrial case study, which provides initial evidence of the feasibility and benefits of the approach.


A paper describing MCP has been submitted to ISSRE-2018.
You can download an archive with the MCP results and the MCP tool from the following URL https://drive.google.com/open?id=17NFzK3wKVPhfXcVGfGN_NcA2yosZFLJt
