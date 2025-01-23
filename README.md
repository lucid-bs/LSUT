# LSUT
Lucidium Standards of Unofficial Tooling to prevent Erronious Behavior and Development Headaches.

# Preamble

> if every old map does the exact same, when its updated workarounds can be done to make the old ones work, if its just done randomly like you might do it, it could cause issues and your maps to break, causing issues for support, and even effect the mods development if time is spent trying to debug your maps that were just made weird in the first place...

[gikmo. (oli) in the Beat Saber Modding Group Discord, January 22nd, 2025 at 2:31 PM EST.](https://discord.com/channels/441805394323439646/441805394323439648/1331707777235685417) This message was delivered to someone attempting to reverse engineer Vivify before its release.

While this message was not directed towards me, the contents directly correlate to the aim of the Lucidium Project and it's library of tooling and scripts. As Lucidium intends to directly interface with the Heck mod suite, Synapse, and Vivify while directly circumventing the use of Unity, it is of utmost importance to recognize the potential risk that comes with an unofficial tool such as this project. 

As Unity's source code is private, **NOTHING THE LUCIDIUM TOOLSET CREATES WILL 100% MATCH WITH ANYTHING UNITY WILL CREATE.** Because of this, ***ALWAYS AND FOREVER*** will there be the potential for game-breaking bugs to occur, which may cause performance issues, crashes, and general headaches for everyone involved; The Player, The Mod Developers, and The Lucidium Developers. These headaches will reflect badly on the Lucidium Toolset and may lead to blocking of maps produced using the Lucidium Toolset. The Lucidium Standards of Unofficial Tooling (LSUT) shall be put in place to prevent the aforementioned headaches.

# Rule 1: Rules and Stadards.

Rules are a set of explicit regulations that developers and users alike shall handle Maps and Tools (defined in Rule 2 of the LSUT) with. 

Standards are a set of regulations that Tools shall use for categorization. ***These Standards must be followed directly, unless explicitly advised by JD The 65th, or a member of the Lucid BS team with proper authorization by JD The 65th to provide input on Developmental Matters provides advisement on non-direct interpretation of the standard.***

These Rules and Standards may be subject to change at any time.

# Rule 2: Handling and Categorization of Tools.
## 2.1: Categorization of Tools.
Tools are any script that as of Map Bake / Compilation, interface with **NON-VANILLA** features of the game. These tools shall be split into 3 categories.
### 2.1.1: Stable Tools.
Stable tools are tools that have been tested using the methods defined in later rules of the LSUT. These tools conform to the LSUT, meeting all of the standards outlined, and have been granted the privilege of Public Access (Being Compiled into Stable Lucidium builds.)
### 2.1.2: Beta Tools.
Beta tools are tools that have met half of the standards outlined in the LSUT. Beta Tools are granted the privilege of Development Access (Accessibility via non-stable branches of the Lucidium Repository and Development/Beta builds.) Beta tools are intended for use of wider testing, and maps using Beta tools **SHALL NOT BE PUBLISHED.** There will be several Metadata markers that Services and Mods can use to detect maps using Beta Tools. Maps using Beta Tools also will have all Map Packing functinalities disabled.
### 2.1.3: Experimental Tools.
Experimental tools are tools that have met less than half of the standards outlined in the LSUT. **Experimental tools are granted zero privilege, and** ***SHALL NOT UNDER ANY CIRCUMSTANCE BE UPLOADED INTO THE MAIN LUCIDIUM REPOSITORY,*** **and shall reside in personal development forks of the Lucidium Repository.**
## 2.2: Tool Metadata.
Tools shall embed usage metadata into ***ALL MAPS*** created using them. Maps **SHALL NOT** be stripped of their usage metadata, and any maps distributed that have been stripped of their usage metadata shall be subject to potential investigation, and punishment if foul play is suspected.
## 2.3: On Demand modification of Tool Status.
A service shall be implemented to ensure the safety of all tools published in Builds using the Lucidium Toolset. If a tool is identified to be potentially harmful (eg, causes unnecessary performance issues, glitches, or crashes), a tool may be "Deranked" using this service. The Lucidium Toolkit shall comply with all modifications to Tool Ranking, and may disable or delete tool access/tool code.
## 2.4: Potential Harmful Tool Investigation.
Tools Identified to be potentially harmful may be subject to seeing their categorization deranked as outlined by Rule 2.3.

# Rule 3: Handling of Maps using the Lucidium Toolset.
Maps shall only be released publicly once all Lucidium Tools used to create the map are categorized as Stable. If maps are consistently released by a user using Non-Stable tools, the Members of the Lucid BS team reserve the right to contact map distribution service operators and request that action be taken against maps released using the Lucidium Toolset and to prevent further maps using the Lucidium Toolset from being distributed. 

If a map is seen to cause reproducable issues, the map shall be taken down and All Tools identified by Tool Metadata shall be subject to further investigation as outlined by Rule 2.4.

# Rule 4: Procedure for Testing Tools.
Tools are to be tested using a variety of inputs and outputs to ensure stability across multiple contexts. Tools should be used in at least 3 example maps to showcase the extent of testing. Tools should also be tested alongside at least 2 other tools (if available) to show unified stability.

# Standards for Testing Tools (STUB)
The following standards shall be used for testing of tools to categorize them.

## Standard 1: Prevention of Non-Practical Behavior
To meet Standard One, a tool must exhibit Practical Behavior. Practical Behavior is behavior that can be reproduced through Regular or Advanced use of Official Tools (eg. Standard Notemods or Shader Magic.) If a tool exhibits behavior that cannot be directly replicated by manual usage of Official Tools, the Tool does not meet this standard.

## Standard 2: Prevention of Unintentionally Non-Deterministic Behavior
To meet Standard Two, a tool must exhibit Artistically Deterministic Behavior. Artistically Deterministic behavior is behavior that unless the user intends for, results in the same exact result under the same exact condtions. Artistically Deterministic behavior does not include behavior that can intentionally cause malicious harm (eg. Intentionally corrupting a User's Map or Game in a non-safe manner that can lead to bugs or crashes.) Artistically Deterministic behavior shall include beahvior that intentionally causes randomness in a safe, controlled manner (eg. Particle Systems or a map such as The 15th Sublimit.) If a tool exhibits Non-Artistically Deterministic behavior, the Tool does not meet this standard.

## Standard 3: Unified Reproducibility
***THIS STANDARD MAY ONLY APPLY TO TOOlS THAT USE APIS THAT DIRECTLY INTERFACE WITH UNITY SYSTEMS, SUCH AS VIVIFY OR SYNAPSE.***

To meet Standard Three, a tool must be tested to provide output that upon Map Bake, ***DOES NOT DIFFER*** from the output of Official Tools. This means that Tools shall be tested to directly output Unity Files that upon Compilation through Official Methods, do not differ from Unofficial Map Baking. If a Tool exhibits behavior that differs from Official Compilation, the tool does not meet this standard.

## Standard 4: Use of Potentially Risky Features
To meet Standard Four, a tool shall not use features that have been deemed by the wider Beat Saber Modding community as features that have the potential harm to cause risky behavior. This means that if a Tool makes use of a feature that is known to cause crashes, create bugs, or exibit unstable behavior, the tool does not meet this standard.

## Standard 5: Stable Behavior.
To meet Standard Four, a tool shall not upon Map Bake, cause behavior that differs across hardware platforms, or causes bugs or crashes that cannot be replicated through the use of Official Tools. This means that if a tool causes a bug or crash that can't be caused using an Official Tool, the tool does not meet this standard.


