# town-of-idiots
Toby, Squirrel Master, and GonkDroid's attempt at a Town of Idiots recode

Town of Idiots roles: 17

Role 1: Bodyguard
  Role Alignment: Town
  Role Type: Protector
  Role Abilities:
    Can choose 1 living player each night to protect. Can only protect self once. If target is attacked, attacker is killed and bodyguard is killed. If bodyguard attempts to protect an executed prisoner, bodyguard does not die. If swordsman attacks target, no one is killed.
  Immune to: None

Role 2: Doctor
  Role Alignment: Town
  Role Type: Blood
  Role Abilities: 
    Can choose 1 living player each night to heal. Can only heal self once. If target is attacked, target survives. Cannot save target from jailer.
  Immune to: None

Role 3: Escort
  Role Alignment: Town
  Role Type: Escort
  Role Abilities:
    Can choose 1 living player each night to roleblock. Target's actions for the night are nullified.
  Immune to: None

Role 4: Vigilante
  Role Alignment: Town
  Role Type: Weaponist
  Role Abilities:
    Can choose 1 living player each night to shoot. Target is killed unless immune or in prison. Cannot shoot self.
  Immune to: None

Role 5: Jailer
  Role Alignment: Town
  Role Type: Protector
  Role Abilities:
    Can choose 1 living player each day to jail. This player is designated a prisoner. Only the jailer can perform actions on the prisoner that night. The jailer may talk to the prisoner during the night. Prisoner does not know who jailer is. Jailer may choose whether or not to execute prisoner. Cannot jail self.
  Immune to: None

Role 6: Veteran
  Role Alignment: Town
  Role Type: Weaponist
  Role Abilities:
    Can choose to be "on call" at night. While on call, all actions performed on the veteran are nullified, and anyone who attempts to perform such actions is killed. Can only be "on call" at most 3 times per game. Cannot be "on call" while in jail.
  Immune to: None while not "on call", all when "on call"

Role 7: Investigator
  Role Alignment: Town
  Role Type: Investigator
  Role Abilities:
    Can choose to investigate one alive player each night. Investigating tells the investigator the target's role type and all possible roles under that role type. If target is framed, investigator will always see a weaponist, unless target is Godfather. Cannot investigate self, for obvious reasons.
  Immune to: None

Role 8: Profiler
  Role Alignment: Town
  Role Type: Vengeance
  Role Abilities:
    Can choose to profile one alive player each night. Profiling tells the profiler whether or not a target is part of the mafia. Only works on framer, mafioso, and swordsman; all other targets are labeled as innocent. Framed targets are labeled mafia.
  Immune to: None

Role 9: Medium
  Role Alignment: Town
  Role Type: Medium
  Role Abilities:
    Can speak to dead players at night. Dead players are not told who the medium is. Upon death, can select a player during the day to seance, in which target can speak to the dead for that single night.
  Immune to: None

Role 10: Lookout
  Role Alignment: Town
  Role Type: Protector
  Role Abilities:
    Can look out for one alive player each night. Looking out tells the lookout who visited the target that night. Can only look out for self once.
  Immune to: None

Role 11: Framer
  Role Alignment: Mafia
  Role Type: Framer
  Role Abilities:
    Can frame one alive player each night. Framing causes the target to appear as a weaponist to the investigator, and a mafia member to the profiler during that night. Cannot frame self. Knows other mafia members but not roles. Can speak to other mafia members at night.
  Immune to: None

Role 12: Mafioso
  Role Alignment: Mafia
  Role Type: Weaponist
  Role Abilities:
    Can shoot one alive player each night. Godfather can tell mafioso who to shoot. Can only shoot self under orders from the godfather. Knows other mafia members but not roles. Can speak to other mafia members at night.
  Immune to: None

Role 13: Godfather
  Role Alignment: Mafia
  Role Type: Godfather
  Role Abilities: 
    Can force Mafioso to shoot one alive player each night. If mafioso is dead, godfather takes gun and directly shoots target. Knows other mafia members but not roles. If in a 1v1 with devil, automatically loses.
  Immune to: All but "on call" veteran, Jailer, and Jester haunting

Role 14: Swordsman
  Role Alignment: Mafia (estranged)
  Role Type: Weaponist
  Role Abilities:
    Can choose to kill one alive player each night. If swordsman attacks bodyguard target, the target, the bodyguard, and the swordsman all survive. Does not know fellow mafia members. Other mafia members do not know who the swordsman is. 
  Immune to: All but "on call" veteran, Jailer, Jester haunting, and Devil

Role 15: Jester
  Role Alignment: Jester (neutral)
  Role Type: Jester
  Role Abilities:
    Goal is to get lynched during the day. If lynched, can haunt one alive player during night (any subsequent night). If jester wins, game continues.
  Immune to: None

Role 16: Executioner
  Role Alignment: Executioner (neutral)
  Role Type: Vengeance
  Role Abilities:
    Has a predetermined target for the entire game. Target has a Town alignment. Goal is to get target lynched. If target is killed during the night, executioner becomes a jester. Thus there can be 2 jesters at a time.
  Immune to: All except jailer (as executioner); as jester, see jester role

Role 17: Devil
  Role Alignment: Devil (neutral)
  Role Type: Blood
  Role Abilities:
    Can choose one alive player to kill each night. Is the only one who can directly kill swordsman. Goal is to be last player alive.
  Immune to: All except "on call" veteran, Jailer, and Jester haunting
