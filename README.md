10 REM ====================================================
20 REM  HADI.BAS :: HADI AGHANDEH, SOFTWARE DEVELOPER
30 REM  BRITISH COLUMBIA, CANADA
40 REM ====================================================
100 PRINT "HADI AGHANDEH"
110 PRINT "Assessment technology and practical AI agents"
120 PRINT
200 PRINT "NOW BUILDING"
210 FOR I = 1 TO 2
220   READ P$, D$, S$
230   PRINT "  "; P$; " ["; S$; "]"
240   PRINT "    "; D$
250 NEXT I
260 PRINT
300 PRINT "STACK"
310 FOR I = 1 TO 5
320   READ A$, T$
330   PRINT "  "; A$; TAB(14); T$
340 NEXT I
350 PRINT
400 PRINT "HOW I WORK"
410 FOR I = 1 TO 3
420   READ R$, W$
430   PRINT "  "; R$; ": "; W$
440 NEXT I
450 PRINT
500 PRINT "SAY HELLO: https://elate.solutions"
510 END
1000 REM ---- PROJECTS: NAME, WHAT IT IS, STATUS ----
1010 DATA "Elate"
1020 DATA "Assessment authoring, delivery, proctoring and scoring"
1030 DATA "LIVE"
1040 DATA "Source-attributed research agent"
1050 DATA "Analyst views from YouTube and news, every claim sourced"
1060 DATA "EARLY STAGE"
2000 REM ---- STACK: AREA, TOOLS ----
2010 DATA "Backend",   "PHP, Laravel"
2020 DATA "Front-end", "JavaScript, Vue.js, Vuetify"
2030 DATA "Data",      "MySQL"
2040 DATA "Cloud",     "AWS"
2050 DATA "Exploring", "AI agents, LLM tooling, research pipelines"
3000 REM ---- PRINCIPLES: RULE, WHY ----
3010 DATA "Attribution over synthesis", "a claim you can't trace is a liability"
3020 DATA "Start simple", "infrastructure follows proven need"
3030 DATA "Honest trade-offs", "'not yet' beats a premature green light"
