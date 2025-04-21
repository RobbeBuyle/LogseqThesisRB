- https://www.dagitty.net/dags.html#
- ```r
  dag {
  bb="0,0,1,1"
  "Automobile accident" [outcome,pos="0.922,0.491"]
  "Cognitive impairment" [outcome,pos="0.338,0.378"]
  "Driving performance (speed management, Lateral deviations)" [outcome,pos="0.685,0.613"]
  "Executive functions" [outcome,pos="0.499,0.544"]
  "Falling asleep behind wheel" [outcome,pos="0.655,0.419"]
  "Jet lag" [exposure,pos="0.047,0.630"]
  "Shift work" [exposure,pos="0.040,0.716"]
  "Sleep debt" [exposure,pos="0.198,0.594"]
  "Sleep fragmentation" [exposure,pos="0.164,0.495"]
  "Sleep quality" [exposure,pos="0.162,0.696"]
  "Time awake" [exposure,pos="0.075,0.423"]
  "Vision impairment" [outcome,pos="0.383,0.478"]
  Age [exposure,pos="0.072,0.919"]
  Attention [outcome,pos="0.472,0.406"]
  Depression [exposure,pos="0.190,0.964"]
  Drowsiness [outcome,pos="0.551,0.754"]
  Fatigue [outcome,pos="0.419,0.754"]
  Insomnia [exposure,pos="0.218,0.106"]
  Medication [exposure,pos="0.300,0.936"]
  Narcolepsy [exposure,pos="0.044,0.162"]
  OSA [exposure,pos="0.089,0.094"]
  RLS [exposure,pos="0.294,0.176"]
  Sex [exposure,pos="0.061,0.827"]
  Sleepiness [outcome,pos="0.369,0.612"]
  TST [exposure,pos="0.037,0.510"]
  Vigilance [outcome,pos="0.463,0.264"]
  "Cognitive impairment" -> "Executive functions"
  "Driving performance (speed management, Lateral deviations)" -> "Automobile accident"
  "Executive functions" -> "Driving performance (speed management, Lateral deviations)"
  "Executive functions" -> Attention
  "Falling asleep behind wheel" -> "Automobile accident"
  "Jet lag" -> "Sleep quality"
  "Jet lag" -> Sleepiness
  "Shift work" -> "Sleep debt"
  "Shift work" -> "Sleep quality"
  "Sleep debt" -> "Sleep quality"
  "Sleep debt" -> Drowsiness
  "Sleep debt" -> Sleepiness
  "Sleep fragmentation" -> Drowsiness
  "Sleep quality" -> Sleepiness
  "Time awake" -> Fatigue
  "Vision impairment" -> "Driving performance (speed management, Lateral deviations)"
  Age -> "Cognitive impairment"
  Age -> "Sleep quality"
  Age -> "Vision impairment"
  Age -> Fatigue
  Attention -> "Driving performance (speed management, Lateral deviations)"
  Depression -> "Cognitive impairment"
  Depression -> "Sleep quality"
  Depression -> Fatigue
  Drowsiness -> "Driving performance (speed management, Lateral deviations)"
  Drowsiness -> "Falling asleep behind wheel"
  Fatigue -> "Driving performance (speed management, Lateral deviations)"
  Fatigue -> "Executive functions"
  Insomnia -> "Sleep debt"
  Insomnia -> "Sleep fragmentation"
  Medication -> "Cognitive impairment"
  Medication -> Drowsiness
  Narcolepsy -> "Cognitive impairment"
  Narcolepsy -> "Falling asleep behind wheel"
  Narcolepsy -> Sleepiness
  OSA -> "Cognitive impairment"
  OSA -> "Sleep fragmentation"
  OSA -> Sleepiness
  RLS -> "Sleep fragmentation"
  Sex -> "Sleep quality"
  Sex -> Fatigue
  Sex -> Sleepiness
  Sleepiness -> "Executive functions"
  Sleepiness -> Drowsiness
  TST -> "Sleep debt"
  Vigilance -> Attention
  }
  
  ```