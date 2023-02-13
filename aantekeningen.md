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
|total.matches|Uniek|
|total.matchesInStart|kan niet hoger zijn dan total.matches|
|total.matchesSubstituted|kan niet hoger zijn dan (total.matches - total.matchesInStart)|
|total.matchesComingOff|kan niet hoger zijn dan total.matches|
|total.minutesOnField|kan niet hoger zijn dan (total.matches * 90)|
|total.minutesTagged|kan niet hoger zijn dan (total.matches * 90)|
|total.goals|Uniek|
|total.assists|Uniek|
|total.shots|Uniek|
|total.headShots|Uniek|
|total.yellowCards|Uniek|
|total.redCards|kan niet hoger zijn dan total.matches|
|total.directRedCards|kan niet hoger zijn dan total.redCards|
|total.penalties|Uniek|
|total.linkupPlays|Uniek|
|total.duels|(total.defensiveDuel + total.offensiveDuels + total.aerialDuels)|
|total.duelsWon|(total.defensiveDuelWon + total.offensiveDuelsWon + total.aerialDuelsWon)|
|total.defensiveDuels|Uniek|
|total.defensiveDuelsWon|Uniek, maar kan niet hoger zijn dan total.defensiveDuels|
|total.offensiveDuels|Uniek|
|total.offensiveDuelsWon|Uniek, maar kan niet hoger zijn dan total.offensiveDuels|
|total.aerialDuels|Uniek|
|total.aerialDuelsWon|Uniek, maar kan niet hoger zijn dan total.aerialDuels|
|total.fouls|Uniek|
|total.passes|
|total.successfulPasses|
|total.smartPasses|Uniek|
|total.successfulSmartPasses|Uniek, maar niet hoger dan total.smartPasses|
|total.passesToFinalThird|Uniek|
|total.successfulPassesToFinalThird|Uniek, maar niet hoger dan total.passesToFinalThird|
|total.crosses|
|total.successfulCrosses|Uniek, maar niet hoger dan total.crosses|
|total.forwardPasses|
|total.successfulForwardPasses|Uniek, maar niet hoger dan total.forwardPasses|
|total.backPasses|
|total.successfulBackPasses|Uniek, maar niet hoger dan total.backPasses|
|total.throughPasses|
|total.successfulThroughPasses|Uniek, maar niet hoger dan total.throughPasses|
|total.keyPasses|
|total.successfulKeyPasses|Uniek, maar niet hoger dan total.keyPasses|
|total.verticalPasses|
|total.successfulVerticalPasses|Uniek, maar niet hoger dan total.verticalPasses|
|total.longPasses|
|total.successfulLongPasses|Uniek, maar niet hoger dan total.longPasses|
|total.dribbles|
|total.successfulDribbles|Uniek, maar niet hoger dan total.dribbles|
|total.interceptions|
|total.defensiveActions|
|total.successfulDefensiveAction|Uniek, maar niet hoger dan total.defensiveActions|
|total.attackingActions|
|total.successfulAttackingActions|Uniek, maar niet hoger dan total.attackingActions|
|total.freeKicks|
|total.freeKicksOnTarget|Uniek, maar niet hoger dan total.freeKicks|
|total.directFreeKicks|
|total.directFreeKicksOnTarget|Uniek, maar niet hoger dan total.directFreeKicks of total.freeKicksOnTarget|
|total.corners|
|total.successfulPenalties|Uniek, maar niet hoger dan total.penalties|
|total.successfulLinkupPlays|Uniek, maar niet hoger dan total.linkupPlays|
|total.accelerations|
|total.pressingDuels|
|total.pressingDuelsWon|Uniek, maar niet hoger dan total.pressingDuels|
|total.looseBallDuels|
|total.looseBallDuelsWon|Uniek, maar niet hoger dan total.looseBallDuels|
|total.missedBalls|
|total.shotAssists|
|total.shotOnTargetAssists|
|total.recoveries|
|total.opponentHalfRecoveries|
|total.dangerousOpponentHalfRecoveries|Uniek, maar niet hoger dan total.opponentHalfRecoveries|
|total.losses|
|total.ownHalfLosses|
|total.dangerousOwnHalfLosses|Uniek, maar niet hoger dan total.ownHalfLosses|
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
|total.successfulProgressivePasses|Uniek, maar niet hoger dan total.progressivePasses|
|total.successfulSlidingTackles|Uniek, maar niet hoger dan total.slidingTackles|
|total.successfulGoalKicks|Uniek, maar niet hoger dan total.goalKicks|
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
|total.successfulLateralPasses|Uniek, maar niet hoger dan total.lateralPasses|