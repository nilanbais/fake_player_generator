# Aantekeningen m.b.t. de waarden van de spelers data.

Averages worden hoogst waardschijnlijk per 90 minuten berekend, in plaats van per gespeelde wedstrijd.
Hier is de parameter total.minutesOnField leidend en niet total.matches.

Waarschijnlijk hoeft niet elke waarde radom bepaald te worden, maar zijn er een aantal leidende
parameters die bepalend zijn voor de waarde van andere parameters. Denk bijvoorbeeld aan de average parameter
t.o.v. de total parameters.
Daarbij zijn er ook parameters die de maximum waarde van een andere parameter bepalen. Denk hierbij aan
total.passes en total.successfulPasses, waarbij de succesvolle passes nooit hoger kan zijn de het 
totaal aantal passes.

## Vragen
Kunnen we voor nu een scenario bedenken waarbij de vergelijkingen binnen dezelfde compotitie gedaan worden?
Zelfde (bovenstaande) geldt voor de positie en het seizoen.


## Paramter Overzicht
|Parameter|Opmerking|
|---------|------------------------|
|total.matches|
|total.matchesInStart|
|total.matchesSubstituted|
|total.matchesComingOff|
|total.minutesOnField|
|total.minutesTagged|
|total.goals|
|total.assists|
|total.shots|
|total.headShots|
|total.yellowCards|
|total.redCards|
|total.directRedCards|
|total.penalties|
|total.linkupPlays|
|total.duels|
|total.duelsWon|
|total.defensiveDuels|
|total.defensiveDuelsWon|
|total.offensiveDuels|
|total.offensiveDuelsWon|
|total.aerialDuels|
|total.aerialDuelsWon|
|total.fouls|
|total.passes|
|total.successfulPasses|
|total.smartPasses|
|total.successfulSmartPasses|
|total.passesToFinalThird|
|total.successfulPassesToFinalThird|
|total.crosses|
|total.successfulCrosses|
|total.forwardPasses|
|total.successfulForwardPasses|
|total.backPasses|
|total.successfulBackPasses|
|total.throughPasses|
|total.successfulThroughPasses|
|total.keyPasses|
|total.successfulKeyPasses|
|total.verticalPasses|
|total.successfulVerticalPasses|
|total.longPasses|
|total.successfulLongPasses|
|total.dribbles|
|total.successfulDribbles|
|total.interceptions|
|total.defensiveActions|
|total.successfulDefensiveAction|
|total.attackingActions|
|total.successfulAttackingActions|
|total.freeKicks|
|total.freeKicksOnTarget|
|total.directFreeKicks|
|total.directFreeKicksOnTarget|
|total.corners|
|total.successfulPenalties|
|total.successfulLinkupPlays|
|total.accelerations|
|total.pressingDuels|
|total.pressingDuelsWon|
|total.looseBallDuels|
|total.looseBallDuelsWon|
|total.missedBalls|
|total.shotAssists|
|total.shotOnTargetAssists|
|total.recoveries|
|total.opponentHalfRecoveries|
|total.dangerousOpponentHalfRecoveries|
|total.losses|
|total.ownHalfLosses|
|total.dangerousOwnHalfLosses|
|total.xgShot|
|total.xgAssist|
|total.xgSave|
|total.receivedPass|
|total.touchInBox|
|total.progressiveRun|
|total.offsides|
|total.clearances|
|total.secondAssists|
|total.thirdAssists|
|total.shotsBlocked|
|total.foulsSuffered|
|total.progressivePasses|
|total.counterpressingRecoveries|
|total.slidingTackles|
|total.goalKicks|
|total.dribblesAgainst|
|total.dribblesAgainstWon|
|total.goalKicksShort|
|total.goalKicksLong|
|total.shotsOnTarget|
|total.successfulProgressivePasses|
|total.successfulSlidingTackles|
|total.successfulGoalKicks|
|total.fieldAerialDuels|
|total.fieldAerialDuelsWon|
|total.gkCleanSheets|
|total.gkConcededGoals|
|total.gkShotsAgainst|
|total.gkExits|
|total.gkSuccessfulExits|
|total.gkAerialDuels|
|total.gkAerialDuelsWon|
|total.gkSaves|
|total.newDuelsWon|
|total.newDefensiveDuelsWon|
|total.newOffensiveDuelsWon|
|total.newSuccessfulDribbles|
|total.lateralPasses|
|total.successfulLateralPasses|