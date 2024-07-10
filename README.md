# Scoutium-Talent-Hunting-Classification-Project

<img src = "images/scoutium_talent_hunting.png" style = "width:1050px; height:440px"/>

## Business Problem

Scoutium is a digital football scouting platform. This platform aims to discover talented players by evaluating their performance and present them to football clubs. The goal of the project is to predict which category (**average** or **highlighted**) football players belong to based on their attributes observed by scouts.

## Dataset Story

The dataset consists of information from Scoutium, which includes the features and scores of the football players evaluated by the scouts according to the characteristics of the footballers observed in the matches.

## Features of Dataset

- **Total Features :** 9
- **Total Row :** 10.730
- **CSV File Size :** 754.6 KB

## Variable Description

**task_response_id:** A set of evaluations by a scout for all players in a team's squad during a match.

**match_id:** The identifier of the relevant match.

**evaluator_id:** The identifier of the evaluator (scout).

**player_id:** The identifier of the relevant player.

**position_id:** The identifier of the position the player played in that match.

- 1: Goalkeeper
- 2: Center-back
- 3: Right-back
- 4: Left-back
- 5: Defensive midfielder
- 6: Central midfielder
- 7: Right winger
- 8: Left winger
- 9: Attacking midfielder
- 10: Forward

**analysis_id:** A set containing evaluations of a player's attributes by a scout in a match.

**attribute_id:** The identifier of each attribute being evaluated for players.

**attribute_value:** The score given by a scout to a player's attribute.

**potential_label:** The label indicating the scout's final decision about a player in a match. (target variable)
