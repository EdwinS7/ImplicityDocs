# CCSPlayer

* `m_flSimulationTime` (integer)
* `m_nSurroundType` (integer)
* `m_vecSpecifiedSurroundingMins` (vector)
* `m_vecSpecifiedSurroundingMaxs` (vector)
* `m_iPendingTeamNum` (integer)
* `m_CollisionGroup` (integer)
* `m_flShadowCastDistance` (float)
* `m_hEffectEntity` (integer)
* `m_bIsScoped` (integer)
* `m_iParentAttachment` (integer)
* `m_iTextureFrameIndex` (integer)
* `m_bSimulatedEveryTick` (integer)
* `m_bAnimatedEveryTick` (integer)
* `m_bAlternateSorting` (integer)
* `m_bSpottedByMask` (integer\[0-1])
* `m_bIsAutoaimTarget` (integer)
* `m_flUseLookAtAngle` (float)
* `m_flLastMadeNoiseTime` (float)
* `m_flMaxFallVelocity` (float)
* `m_bEligibleForScreenHighlight` (integer)
* `m_flPoseParameter` (float\[0-23])
* `m_flEncodedController` (float\[0-3])
* `m_bClientSideAnimation` (integer)
* `m_bClientSideFrameReset` (integer)
* `m_bClientSideRagdoll` (integer)
* `m_nNewSequenceParity` (integer)
* `m_nResetEventsParity` (integer)
* `m_nMuzzleFlashParity` (integer)
* `m_hLightingOrigin` (integer)
* `m_bSuppressAnimSounds` (integer)
* `m_nHighlightColorR` (integer)
* `m_nHighlightColorG` (integer)
* `m_nHighlightColorB` (integer)
* `m_flexWeight` (float\[0-95])
* `m_hActiveWeapon` (integer)
* `m_flTimeOfLastInjury` (float)
* `m_hMyWeapons` (integer\[0-63])
* `m_hMyWearables` (integer\[0])
* `m_nRelativeDirectionOfLastInjury` (integer)
* `m_afPhysicsFlags` (integer)
* `m_hGroundEntity` (integer)
* `m_iBonusProgress` (integer)
* `m_iBonusChallenge` (integer)
* `m_iObserverMode` (integer)
* `m_bActiveCameraMan` (integer)
* `m_bCameraManXRay` (integer)
* `m_bCameraManOverview` (integer)
* `m_bCameraManScoreBoard` (integer)
* `m_uCameraManGraphs` (integer)
* `m_iCoachingTeam` (integer)
* `m_hObserverTarget` (integer)
* `m_szLastPlaceName` (string)
* `m_vecLadderNormal` (vector)
* `m_ladderSurfaceProps` (integer)
* `m_ubEFNoInterpParity` (integer)
* `m_iDeathPostEffect` (integer)
* `m_hPostProcessCtrl` (integer)
* `m_hColorCorrectionCtrl` (integer)
* `m_PlayerFog.m_hCtrl` (integer)
* `m_vphysicsCollisionState` (integer)
* `m_bShouldDrawPlayerWhileUsingViewEntity` (integer)
* `m_chAreaBits` (integer\[0-31])
* `m_chAreaPortalBits` (integer\[0-23])
* `m_nDuckTimeMsecs` (integer)
* `m_nDuckJumpTimeMsecs` (integer)
* `m_nJumpTimeMsecs` (integer)
* `m_viewPunchAngle` (vector)
* `m_aimPunchAngleVel` (vector)
* `m_bDrawViewmodel` (integer)
* `m_bAllowAutoMovement` (integer)
* `m_skybox3d.scale` (integer)
* `m_skybox3d.origin` (vector)
* `m_skybox3d.area` (integer)
* `m_skybox3d.fog.enable` (integer)
* `m_skybox3d.fog.blend` (integer)
* `m_skybox3d.fog.dirPrimary` (vector)
* `m_skybox3d.fog.colorPrimary` (integer)
* `m_skybox3d.fog.colorSecondary` (integer)
* `m_skybox3d.fog.start` (float)
* `m_skybox3d.fog.end` (float)
* `m_skybox3d.fog.maxdensity` (float)
* `m_skybox3d.fog.HDRColorScale` (float)
* `m_audio.localSound[0]` (vector)
* `m_audio.localSound[1]` (vector)
* `m_audio.localSound[2]` (vector)
* `m_audio.localSound[3]` (vector)
* `m_audio.localSound[4]` (vector)
* `m_audio.localSound[5]` (vector)
* `m_audio.localSound[6]` (vector)
* `m_audio.localSound[7]` (vector)
* `m_audio.soundscapeIndex` (integer)
* `m_audio.localBits` (integer)
* `m_audio.entIndex` (integer)
* `m_vecViewOffset[0]` (float)
* `m_vecViewOffset[1]` (float)
* `m_vecViewOffset[2]` (float)
* `m_nNextThinkTick` (integer)
* `m_vecBaseVelocity` (vector)
* `m_hConstraintEntity` (integer)
* `m_vecConstraintCenter` (vector)
* `m_flConstraintRadius` (float)
* `m_flConstraintWidth` (float)
* `m_flConstraintSpeedFactor` (float)
* `m_bConstraintPastRadius` (integer)
* `m_flNextDecalTime` (float)
* `m_flLaggedMovementValue` (float)
* `m_hTonemapController` (integer)
* `m_flPoseParameter` (integer)
* `m_flPlaybackRate` (integer)
* `m_nNewSequenceParity` (integer)
* `m_nResetEventsParity` (integer)
* `m_nMuzzleFlashParity` (integer)
* `m_nNumFastDucks` (integer)
* `m_bDuckOverride` (integer)
* `m_bPlayerDominated` (integer\[0-64])
* `m_bPlayerDominatingMe` (integer\[0-64])
* `m_flVelocityModifier` (float)
* `m_iWeaponPurchasesThisRound` (integer\[0-255])
* `m_unActiveQuestId` (integer)
* `m_nQuestProgressReason` (integer)
* `m_iWeaponPurchasesThisMatch` (integer\[0-255])
* `m_EquippedLoadoutItemDefIndices` (integer\[0-56])
* `m_angEyeAngles[0]` (float)
* `m_angEyeAngles[1]` (float)
* `m_iPrimaryAddon` (integer)
* `m_iSecondaryAddon` (integer)
* `m_iThrowGrenadeCounter` (integer)
* `m_bWaitForNoAttack` (integer)
* `m_bIsRespawningForDMBonus` (integer)
* `m_iStartAccount` (integer)
* `m_totalHitsOnServer` (integer)
* `m_bInNoDefuseArea` (integer)
* `m_bKilledByTaser` (integer)
* `m_bNightVisionOn` (integer)
* `m_bHasNightVision` (integer)
* `m_bInHostageRescueZone` (integer)
* `m_bIsGrabbingHostage` (integer)
* `m_iBlockingUseActionInProgress` (integer)
* `m_nIsAutoMounting` (integer)
* `m_fImmuneToGunGameDamageTime` (float)
* `m_bGunGameImmunity` (integer)
* `m_bHasMovedSinceSpawn` (integer)
* `m_bMadeFinalGunGameProgressiveKill` (integer)
* `m_iGunGameProgressiveWeaponIndex` (integer)
* `m_iNumGunGameTRKillPoints` (integer)
* `m_iNumGunGameKillsWithCurrentWeapon` (integer)
* `m_iNumRoundKills` (integer)
* `m_fMolotovUseTime` (float)
* `m_fMolotovDamageTime` (float)
* `m_hCarriedHostage` (integer)
* `m_hCarriedHostageProp` (integer)
* `m_flGroundAccelLinearFracLastTime` (float)
* `m_flGuardianTooFarDistFrac` (float)
* `m_flDetectedByEnemySensorTime` (float)
* `m_bCanMoveDuringFreezePeriod` (integer)
* `m_isCurrentGunGameLeader` (integer)
* `m_isCurrentGunGameTeamLeader` (integer)
* `m_passiveItems` (integer\[0-3])
* `m_bIsPlayerGhost` (integer)
* `m_bHasHeavyArmor` (integer)
* `m_nHeavyAssaultSuitCooldownRemaining` (integer)
* `m_flFlashDuration` (float)
* `m_flFlashMaxAlpha` (float)
* `m_iProgressBarDuration` (integer)
* `m_flProgressBarStartTime` (float)
* `m_unCurrentEquipmentValue` (integer)
* `m_unRoundStartEquipmentValue` (integer)
* `m_unFreezetimeEndEquipmentValue` (integer)
* `m_bIsControllingBot` (integer)
* `m_bHasControlledBotThisRound` (integer)
* `m_bCanControlObservedBot` (integer)
* `m_iControlledBotEntIndex` (integer)
* `m_bHud_MiniScoreHidden` (integer)
* `m_bHud_RadarHidden` (integer)
* `m_nLastKillerIndex` (integer)
* `m_nLastConcurrentKilled` (integer)
* `m_nDeathCamMusic` (integer)
* `m_bIsLookingAtWeapon` (integer)
* `m_bIsHoldingLookAtWeapon` (integer)
* `m_iNumRoundKillsHeadshots` (integer)
* `m_iMatchStats_Kills` (integer\[0-29])
* `m_iMatchStats_Damage` (integer\[0-29])
* `m_iMatchStats_EquipmentValue` (integer\[0-29])
* `m_iMatchStats_MoneySaved` (integer\[0-29])
* `m_iMatchStats_KillReward` (integer\[0-29])
* `m_iMatchStats_LiveTime` (integer\[0-29])
* `m_iMatchStats_Deaths` (integer\[0-29])
* `m_iMatchStats_Assists` (integer\[0-29])
* `m_iMatchStats_HeadShotKills` (integer\[0-29])
* `m_iMatchStats_Objective` (integer\[0-29])
* `m_iMatchStats_CashEarned` (integer\[0-29])
* `m_iMatchStats_UtilityDamage` (integer\[0-29])
* `m_unTotalRoundDamageDealt` (integer)
* `m_iMatchStats_EnemiesFlashed` (integer\[0-29])
* `m_flLowerBodyYawTarget` (float)
* `m_flThirdpersonRecoil` (float)
* `m_bHideTargetID` (integer)
* `m_bIsSpawnRappelling` (integer)
* `m_vecSpawnRappellingRopeOrigin` (vector)
* `m_nSurvivalTeam` (integer)
* `m_hSurvivalAssassinationTarget` (integer)
* `m_vecAutomoveTargetEnd` (vector)
* `m_flAutoMoveStartTime` (float)
* `m_flAutoMoveTargetTime` (float)
* `m_flHealthShotBoostExpirationTime` (float)
* `m_flLastExoJumpTime` (float)
