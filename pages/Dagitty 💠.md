- ```r
  dag {
  bb="0,0,1,1"
  "Automobile accident" [outcome,pos="0.922,0.491"]
  "Cognitive impairment" [outcome,pos="0.383,0.385"]
  "Driving performance (speed management, Lateral deviations)" [outcome,pos="0.684,0.613"]
  "Executive functions" [outcome,pos="0.449,0.446"]
  "Falling asleep behind wheel" [outcome,pos="0.678,0.434"]
  "Jet lag" [exposure,pos="0.047,0.630"]
  "Shift work" [exposure,pos="0.040,0.716"]
  "Sleep debt" [exposure,pos="0.242,0.592"]
  "Sleep fragmentation" [exposure,pos="0.194,0.477"]
  "Sleep quality" [exposure,pos="0.184,0.689"]
  "Time awake" [exposure,pos="0.060,0.452"]
  "Vision impairment" [outcome,pos="0.388,0.499"]
  Age [exposure,pos="0.100,0.902"]
  Attention [outcome,pos="0.492,0.400"]
  Depression [exposure,pos="0.175,0.968"]
  Drowsiness [outcome,pos="0.506,0.851"]
  Fatigue [outcome,pos="0.371,0.838"]
  Insomnia [exposure,pos="0.218,0.106"]
  Medication [exposure,pos="0.272,0.945"]
  Narcolepsy [exposure,pos="0.065,0.230"]
  OSA [exposure,pos="0.126,0.161"]
  RLS [exposure,pos="0.294,0.176"]
  Sex [exposure,pos="0.061,0.827"]
  Sleepiness [outcome,pos="0.439,0.683"]
  TST [exposure,pos="0.046,0.537"]
  Vigilance [outcome,pos="0.472,0.309"]
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
  "Sleep quality" <-> Depression
  "Time awake" -> Fatigue
  "Vision impairment" -> "Driving performance (speed management, Lateral deviations)"
  Age -> "Cognitive impairment"
  Age -> "Sleep quality"
  Age -> "Vision impairment"
  Age -> Fatigue
  Attention -> "Driving performance (speed management, Lateral deviations)"
  Depression -> "Cognitive impairment"
  Depression -> Fatigue
  Drowsiness -> "Driving performance (speed management, Lateral deviations)"
  Drowsiness -> "Falling asleep behind wheel"
  Fatigue -> "Driving performance (speed management, Lateral deviations)"
  Fatigue -> "Executive functions"
  Fatigue -> Drowsiness
  Insomnia -> "Sleep debt"
  Insomnia -> "Sleep fragmentation"
  Medication -> "Cognitive impairment"
  Medication -> Drowsiness
  Narcolepsy -> "Cognitive impairment"
  Narcolepsy -> "Falling asleep behind wheel"
  Narcolepsy -> Sleepiness
  OSA -> "Sleep fragmentation"
  OSA -> Sleepiness
  RLS -> "Sleep fragmentation"
  Sex -> "Sleep quality"
  Sex -> Fatigue
  Sex -> OSA
  Sleepiness -> "Driving performance (speed management, Lateral deviations)"
  Sleepiness -> "Executive functions"
  Sleepiness -> "Falling asleep behind wheel"
  Sleepiness -> Drowsiness
  TST -> "Sleep debt"
  Vigilance -> Attention
  }
  
  ```
- <iframe src="https://www.dagitty.net/dags.html" style="width: 100%; height: 600px"></iframe>