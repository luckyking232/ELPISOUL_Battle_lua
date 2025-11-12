# Lua Scripts Documentation

自动生成于 2025-11-12 23:18:18


## 模块与函数

### 模块：`BattleAction`

- `BattleAction.ClearAttackInfo(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealAttack(attackUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealAttackOver(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealBeatBack(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealBuffPre()`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealBuffRemove(battleUnit, buff)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealBuffSettle(battleUnit, buff)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealCheckSkill(battleUnit, targetUid)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealDamageToTreat(damage, defUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealDead(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealDevour(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealDying(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealFear(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealHurt(attackUnit, defUnit, num, hurtDisplayType, hurtExtraParams, hurtEffectParams, hurtEffectFlip)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealMove(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealMoveToAttack(attackUnit, hurtUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealPortal(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealPreBattle()`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealRageChange(battleUnit, num)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealRevive(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealSpecial(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealSpecialEnd(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealStand(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealStart(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealStopAttack(battleUnit, changeToState)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealStopMove(battleUnit, changeToState)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealSummon(data, triggerBuff)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealTrick(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealTriggerBurstSkill(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealTriggerPassiveSkill(battleUnit, specificCondition, skillList, triggerFromUnitUid, triggerParams)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealTriggerSkill(battleUnit, specificCondition, skillList, triggerFromUnitUid, triggerParams)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealTriggerSkillCondition(battleUnit, skillId, skillLevelUpConfig, specificCondition, triggerFromUnitUid, triggerParams)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealUnitBasicBuff(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealUnitSkill(battleUnit, skillId, skillLevelUpConfig, skillTargetUidList, isFromSkillWait, specificCondition, triggerFromUnitUid)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.DealWaitAttack(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.ForceChangeState(battleUnit, changeToState, triggerBuff)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.InitBeatBackUnitData(battleUnit, fromUnit, buffConfig)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.InitDevourUnitData(battleUnit, fromUnit, buffConfig)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.InitFearUnitData(battleUnit, buffConfig)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.InitLocalVar()`  —  文件: `BattleAction.lua.lua`
- `BattleAction.IsIgnoreTargetInRange(battleUnit, skillId)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.UpdateModelFlipWhenAttack(battleUnit)`  —  文件: `BattleAction.lua.lua`
- `BattleAction.UpdateModelTimescale(battleUnit, forceUpdateDisplay)`  —  文件: `BattleAction.lua.lua`

### 模块：`BattleActionDisplay`

- `BattleActionDisplay.AddWaitDealEffect(fromUnit, targetUnit, name, path, autoDestroy, bindSlot, rotationAroundY)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.AddWaitDealSound(path, bank, model, loopSound_BuffUid)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.AddWaitDealVoice(unitUid, bubbleType)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.AddWaitDealWarningEffect(unit, path, targetType, rangeType, rangeX, rangeY, index, totalFrame)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.ClearAction()`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.ClearAttackDisplay(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.ClearSkillEffect(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.DealWaitAction()`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.GetUnitRotation(targetUnit, fromUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.GetWaitWarningEffectIndex()`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.Init()`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.InitLocalVar()`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayAttack(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayBeatBack(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayBeatBackTrapState(battleUnit, model, angle, z_dis)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayBuffEffect(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayBuffIconRefresh(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayBuffWords(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayDead(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayDestroy(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayDevour(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayFear(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayHitEffect(attackUnit, defUnit, hurtEffectParams, hurtEffectFlip)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayHurt(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayMove(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayPersistCast(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayRage(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayRandomHit(battleUnit, randomHit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayRevive(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlaySpecial(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayStand(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayStart(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayStun(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayTransform(battleUnit, transformEffect, sound, callback, pause)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.PlayWaitAttack(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.ShowFreezeDisplay(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.ShowPetrifiedDisplay(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.ShowStealthDisplay(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.UpdateControlDisplay(battleUnit, interval)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.UpdateModelFlipWhenAttack(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`
- `BattleActionDisplay.UpdateModelTimescale(battleUnit)`  —  文件: `BattleActionDisplay.lua.lua`

### 模块：`BattleAxisWindow`

- `BattleAxisWindow.ClickDeathBtn()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.ClickHand(camp, index, headType)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.ClickManuallySkillBtn()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.ClickRoundBtn(eventContext)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.ClickSpecialSkillBtn()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.ClickUniqueSkillBtn()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.CloseHeadTips()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.CloseSkillTips()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.CreateBurst()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.CreateBurstCardSkill()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.CreateDeathSkill()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.CreateHand(camp, index, headType)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.CreateHead(camp, leftCom, rightCom, unitInfo, manuallySkillInfo, stateTxt)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.CreateManuallySkill()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.CreateSmallSkill()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.CreateUniqueSkill()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.CreateWaveList()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.GetShowHeadDataList(camp, index, headType)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.HandleMessage(msgId, para)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.InitBtn()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.InitComp()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.InitTimelineData()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.IsMonster(id)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.IsWin()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.OnClose()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.OnHide()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.OnInit(bridgeObj)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.OnShown()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.ReInitData()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.ShowSkillTips(skillId, skillLevel)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.UpdateAll(index)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.UpdateBattleData(index)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.UpdateHead(head, unitInfo, manuallySkillInfo, stateTxt, touchable)`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.UpdateHeadVisible()`  —  文件: `BattleAxisWindow.lua.lua`
- `BattleAxisWindow.UpdateInfo()`  —  文件: `BattleAxisWindow.lua.lua`

### 模块：`BattleBackground`

- `BattleBackground.Clear()`  —  文件: `BattleBackground.lua.lua`
- `BattleBackground.Init()`  —  文件: `BattleBackground.lua.lua`

### 模块：`BattleBomb`

- `BattleBomb.InitLocalVar()`  —  文件: `BattleBomb.lua.lua`
- `BattleBomb.NewBomb(showDisplayConfig, fromUnit, targetUnit, skillId, subSkillId, bombExtraParams)`  —  文件: `BattleBomb.lua.lua`

### 模块：`BattleBuff`

- `BattleBuff.InitLocalVar()`  —  文件: `BattleBuff.lua.lua`
- `BattleBuff.NewBuff(_id, _from, _to, _settleNow, _extraParams, _delayParams)`  —  文件: `BattleBuff.lua.lua`

### 模块：`BattleBuffEffect`

- `BattleBuffEffect.DealBeAffectedWithEffect(effect, finalValue)`  —  文件: `BattleBuffEffect.lua.lua`
- `BattleBuffEffect.GetEffectValue(effect, params, getValueParams)`  —  文件: `BattleBuffEffect.lua.lua`
- `BattleBuffEffect.InitLocalVar()`  —  文件: `BattleBuffEffect.lua.lua`
- `BattleBuffEffect.NewEffect(effectStr, belongBuffUid)`  —  文件: `BattleBuffEffect.lua.lua`

### 模块：`BattleBuffMgr`

- `BattleBuffMgr.AddToBuffList(buff)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.AnalysisBuffList(buffList, buffFrom, buffTos, settleNow, extraParams)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.ClearAllBuff()`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.ClearBuffByBuffId(battleUnit, buffId, cleanLimit)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.ClearBuffByEffectId(battleUnit, effectId, cleanLimit)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.ContainEffectId(unit, effectId, bullet)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.DealBulletDirectDamage(from, to)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.DealBulletFinalDamageAdd(fromUnit, fromBullet, toBullet)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetAliveUnitCountByCamp(camp)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetAllBombBuff(skillLevelUpConfig, from, to, settleNow)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetAllBuff(skillLevelUpConfig, from, defUnitUidList, settleNow, extraParams)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetAllBulletBuff(skillLevelUpConfig, from, to, settleNow)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetAllBurstBuff(skillLevelUpConfig, from)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetBombContainedEffect(bomb, effectId, containBuff, returnEffect, returnBuff)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetBuffByUid(uid)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetBuffCountByCampAndId(camp, effectId)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetBuffCountByUnitAndTag(unit, tag)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetBuffGlobalIndex()`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetBuffValue(unit, buffId)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetContainedEffect(unit, effectId, bullet, containBuff, returnEffect, returnBuff)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetEffectCountByCampAndTag(camp, effectTag)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetForceControlEffectIdList()`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetListenerDeduceList(deduceType, toUnitUid, toBulletUid, toBombUid, toCamp)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetListenerRemoveList(removeType)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetListenerSettleList(settleType, fromUnitUid)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetSavedBuffList()`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetSettledBuffByCampAndEffectID(camp, effectId, sortFunc)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetSettledBuffByCampAndEffectTag(camp, effectTag, sortFunc)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetSettledBuffByCampAndId(camp, buffId, sortFunc)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetSettledBuffByCampAndType(camp, type, sortFunc)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetSettledBuffByUnitAndEffectID(unit, effectId, sortFunc, onlyCount)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetSettledBuffByUnitAndEffectTag(unit, effectTag, sortFunc)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetSettledBuffByUnitAndId(unit, buffId, sortFunc)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetSettledBuffByUnitAndType(unit, type, sortFunc)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetSummonCountByCamp(camp)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetUnitListContainEffect(effectId, camp)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetValueByCampAndId(camp, effectId)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.GetValueById(unit, effectId, bullet, params, bomb)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.Init(isStart)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.InitLocalVar()`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.IsBuffImmune(unit, newBuff)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.IsContainBuffFromBuffUid(unit, uid)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.IsUnitImmuneAllHurt(unit)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.IsUnitImmuneBuffHurt(unit)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.IsUnitInvincible(unit)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.IsUnitStealth(unit)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.IsUnitUntreatable(unit)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.IsUnitUnyielding(unit)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.NewBuff(...)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.RefreshRegisterDeduceListener(buff)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.RegisterDeduceListener(buff)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.RegisterRemoveListener(buff)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.RegisterSettleListener(buff)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.RemoveFromBuffList(uid)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.TriggerBombListener(bomb, deduceType)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.TriggerBulletListener(bullet, deduceType, deduceParam)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.TriggerCampListener(camp, deduceType, deduceParam)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.TriggerListener(deduceType, deduceParam)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.TriggerListenerBuffAdd(deduceType, deduceParam)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.TriggerRemoveListener(removeType, params)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.TriggerUnitListener(unit, deduceType, settleType, deduceParam, settleParam)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.UnRegisterDeduceListener(uid, deduceType)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.UnRegisterRemoveListener(uid, removeType)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.UnRegisterSettleListener(uid, settleType)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.UnRegisterSettleListenerByUnitUid(unitUid)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.UpdateAllBuff(curFixedFrame)`  —  文件: `BattleBuffMgr.lua.lua`
- `BattleBuffMgr.UpdateUnitBuffShield(unit, hurt)`  —  文件: `BattleBuffMgr.lua.lua`

### 模块：`BattleBullet`

- `BattleBullet.InitLocalVar()`  —  文件: `BattleBullet.lua.lua`
- `BattleBullet.NewBullet(showDisplayConfig, fromUnit, defUnit, fromPos, toPos, subSkillId, skillId, speed, bulletExtraParams)`  —  文件: `BattleBullet.lua.lua`

### 模块：`BattleBurst`

- `BattleBurst.InitLocalVar()`  —  文件: `BattleBurst.lua.lua`
- `BattleBurst.NewBurst(burstId, camp)`  —  文件: `BattleBurst.lua.lua`

### 模块：`BattleBurstSkill`

- `BattleBurstSkill.InitLocalVar()`  —  文件: `BattleBurstSkill.lua.lua`
- `BattleBurstSkill.NewSkill(skillId, camp, burstId)`  —  文件: `BattleBurstSkill.lua.lua`

### 模块：`BattleCamp`

- `BattleCamp.DealCampCharge(camp, hurt)`  —  文件: `BattleCamp.lua.lua`
- `BattleCamp.NewCamp(camp)`  —  文件: `BattleCamp.lua.lua`

### 模块：`BattleChoose`

- `BattleChoose.GetAllSummonBySide(camp, includeBuilding)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetAllSummonByUnit(unit)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetBuffMaxOverlayUnreachedCards(atkUnit, isSameSide, effectId, notIncludeSelf)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetBuffTargetUnitList(from, tos, targetId, buffConfig, chooseExtraParams)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetBulletHurtUnitList(bullet)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetContainEffectIdCards(atkUnit, isSameSide, effectId, notIncludeSelf, reverse, includeBuilding)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetDyingUnitList(atkUnit, isSameSide, num, notIncludeSelf)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetGridByRatio(camp, ratio)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetMinHpPerUnit(atkUnit, battleUnitType)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetNearestUnit(selfUnit, isSameSide, unitTypeList, numLimit, isReverse, notIncludeSelf, notIncludeUid, includeBuilding, notIncludeUnitType, unitList)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetNotSummonUnit(unitList)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetRandomGridList(randomNum)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetRandomSort(list)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetRandomUnitList(atkUnit, isSameSide, randomNum, unitTypeList, notIncludeSelf, elementType, notIncludeUid, notIncludeUnitType, cardsList)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetRangeInfo(skillLevelUpConfig, buffConfig, fromUnit)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetSameCampCardListWithHp(unit)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetSkillTargetUnitList(from, tos, skillLevelUpConfig, chooseExtraParams)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetSummonUnit(unitList)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetTargetType(skillLevelUpConfig, fromUnit)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetTargetUnitList(targetId, from, tos, skillLevelUpConfig, buffConfig, chooseExtraParams)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetTopAtkSpdUnitList(atkUnit, isSameSide, topNum, isReverse, notIncludeSelf)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetTopAtkUnitList(atkUnit, isSameSide, topNum, isReverse, notIncludeSelf, unitList)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetTopBuffEffectTagCountUnitList(atkUnit, isSameSide, tag, number, notIncludeSelf)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetTopDefUnitList(atkUnit, isSameSide, topNum, isReverse, notIncludeSelf, unitList)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetTopHpUnitList(atkUnit, isSameSide, topNum, isReverse, notIncludeSelf, unitTypeList, listForChoose)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetTopMoveSpdUnitList(atkUnit, isSameSide, topNum, isReverse, notIncludeSelf, unitList)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetUnitFor2621(selfUnit)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetUnitForChooseMoveTarget(selfUnit)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetUnitListBySide(atkUnit, isSameSide, unitTypeList, notIncludeSelf, elementType, notIncludeUid, notIncludeUnitType, includeDying, includeBuilding, chooseExtraParams)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetUnitListByType(atkUnit, isSameSide, sortFunc, unitTypeList, findStop, includeBuilding)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetUnitListContainEffectTag(atkUnit, isSameSide, tag, notIncludeSelf, isReverse)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetUnitListForUnit10064(camp)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.GetUnitsFor3120(selfUnit, isSameSide, numLimit, isReverse)`  —  文件: `BattleChoose.lua.lua`
- `BattleChoose.InitLocalVar()`  —  文件: `BattleChoose.lua.lua`

### 模块：`BattleControl`

- `BattleControl.Continue()`  —  文件: `BattleControl.lua.lua`
- `BattleControl.Init()`  —  文件: `BattleControl.lua.lua`
- `BattleControl.InitLocalVar()`  —  文件: `BattleControl.lua.lua`
- `BattleControl.Pause(isBurstPause, isGuidePause)`  —  文件: `BattleControl.lua.lua`
- `BattleControl.SlowTime(timescale)`  —  文件: `BattleControl.lua.lua`
- `BattleControl.Start(delayClearScene)`  —  文件: `BattleControl.lua.lua`
- `BattleControl.Stop(isManual, forceClose)`  —  文件: `BattleControl.lua.lua`
- `BattleControl.UniqueSkillPause(isPause, unit)`  —  文件: `BattleControl.lua.lua`
- `BattleControl.UpdateDisplay()`  —  文件: `BattleControl.lua.lua`
- `BattleControl.UpdateProcess()`  —  文件: `BattleControl.lua.lua`
- `BattleControl.UpdateProcess_2(curFixedFrame)`  —  文件: `BattleControl.lua.lua`

### 模块：`BattleData`

- `BattleData.CacheChallengeStageRsp(data)`  —  文件: `BattleData.lua.lua`
- `BattleData.Clear()`  —  文件: `BattleData.lua.lua`
- `BattleData.ClearCachedChallengeStageRsp()`  —  文件: `BattleData.lua.lua`
- `BattleData.GetAllUnitData()`  —  文件: `BattleData.lua.lua`
- `BattleData.GetRandomForAutoSkill()`  —  文件: `BattleData.lua.lua`
- `BattleData.GetRandomForChooseGrid()`  —  文件: `BattleData.lua.lua`
- `BattleData.GetRandomForChooseShowDisplay()`  —  文件: `BattleData.lua.lua`
- `BattleData.GetRandomForDisplay()`  —  文件: `BattleData.lua.lua`
- `BattleData.GetRandomSeed()`  —  文件: `BattleData.lua.lua`
- `BattleData.GetRandomSeed2()`  —  文件: `BattleData.lua.lua`
- `BattleData.GetRogueAliveCountByType(unitType)`  —  文件: `BattleData.lua.lua`
- `BattleData.GetSkillShowIdFromGroup(id, fashionId)`  —  文件: `BattleData.lua.lua`
- `BattleData.InitData(isClear)`  —  文件: `BattleData.lua.lua`
- `BattleData.IsBattleNoFail(sceneType)`  —  文件: `BattleData.lua.lua`
- `BattleData.IsBattlePVP(sceneType)`  —  文件: `BattleData.lua.lua`
- `BattleData.IsEffectSkill(skillEffectType)`  —  文件: `BattleData.lua.lua`
- `BattleData.IsGuildTrain(sceneType)`  —  文件: `BattleData.lua.lua`
- `BattleData.SortUnitListInit(list)`  —  文件: `BattleData.lua.lua`
- `BattleData.UpdateBattleScore(unit, damage)`  —  文件: `BattleData.lua.lua`

### 模块：`BattleDataCount`

- `BattleDataCount.DealBuffEffect(atkUnit, defUnit, hurt, skillType, isBuff, extraParams, subSkillId, hurtIndex, params)`  —  文件: `BattleDataCount.lua.lua`
- `BattleDataCount.DealSpecialDamageAdd(atkUnit, defUnit, hurt, extraParams, skillType, params)`  —  文件: `BattleDataCount.lua.lua`
- `BattleDataCount.GetManuallySkillHurt(skill, subSkillId, defUid)`  —  文件: `BattleDataCount.lua.lua`
- `BattleDataCount.GetSkillHurt(skillId, subSkillId, atkUnit, defUnit, bulletParams, hurtIndex, params)`  —  文件: `BattleDataCount.lua.lua`
- `BattleDataCount.Init()`  —  文件: `BattleDataCount.lua.lua`
- `BattleDataCount.InitLocalVar()`  —  文件: `BattleDataCount.lua.lua`
- `BattleDataCount.PanDingKeZhiBuff(effect, defUnit)`  —  文件: `BattleDataCount.lua.lua`

### 模块：`BattleDataWindow`

- `BattleDataWindow.ClickRoundBtn(eventContext)`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.CloseWindow()`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.CreateWaveList()`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.GetKilledCountByUid(uid)`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.HandleMessage(msgId, para)`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.InitDamageData()`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.InitTextAndBtn()`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.IsWin()`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.OnClose()`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.OnHide()`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.OnInit(bridgeObj)`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.OnShown()`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.ReInitData()`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.RefreshBtn(clickBtn, camp, sortFunc, sortFuncRevert)`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.RefreshSkillBtn(clickBtn, camp, sortFunc, sortFuncRevert)`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.SwitchData()`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.UpdateAll(index)`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.UpdateBattleData(index)`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.UpdateList(list, damageInfo)`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.UpdateOneItem(hand, damageInfo)`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.UpdateSkillInfo()`  —  文件: `BattleDataWindow.lua.lua`
- `BattleDataWindow.UpdateUnitInfo()`  —  文件: `BattleDataWindow.lua.lua`

### 模块：`BattleFinishFailWindow`

- `BattleFinishFailWindow.CloseWindow()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.HandleMessage(msgId, para)`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.InitBtn()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.OnClose()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.OnHide()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.OnInit(bridgeObj)`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.OnShown()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.OpenAxisWindow()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.OpenDataWindow()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.ReInitData()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.StopTalk()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.TryAgain()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.UpdateAutoBtnText()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.UpdateCardVoice()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.UpdateInfo()`  —  文件: `BattleFinishFailWindow.lua.lua`
- `BattleFinishFailWindow.UpdateResult()`  —  文件: `BattleFinishFailWindow.lua.lua`

### 模块：`BattleFinishWindow`

- `BattleFinishWindow.CancelSave()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.CloseWindow()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.DelayedCall()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.HandleMessage(msgId, para)`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.InitBtn()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.InitText()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.IsOver()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.IsWin()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.OnClose()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.OnHide()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.OnInit(bridgeObj)`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.OnShown()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.OpenAxisWindow()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.OpenDataWindow()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.ReInitData()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.ShowDamage()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.ShowDamageInGuildWar()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.ShowDamageInRaidBoss()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.Sort(a, b)`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.StopTalk()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.UpdateAutoBtnText()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.UpdateCardShow()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.UpdateExp()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.UpdateInfo()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.UpdateItem()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.UpdateResult()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.UpdateSceneType()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.UpdateShowLevelUp()`  —  文件: `BattleFinishWindow.lua.lua`
- `BattleFinishWindow.UpdateTarget()`  —  文件: `BattleFinishWindow.lua.lua`

### 模块：`BattleGrid`

- `BattleGrid.InitLocalVar()`  —  文件: `BattleGrid.lua.lua`
- `BattleGrid.NewGrid(indexX, indexY)`  —  文件: `BattleGrid.lua.lua`

### 模块：`BattleHurtNum`

- `BattleHurtNum.ClearHurtNum()`  —  文件: `BattleHurtNum.lua.lua`
- `BattleHurtNum.ClearPool()`  —  文件: `BattleHurtNum.lua.lua`
- `BattleHurtNum.HideAll()`  —  文件: `BattleHurtNum.lua.lua`
- `BattleHurtNum.Init()`  —  文件: `BattleHurtNum.lua.lua`
- `BattleHurtNum.SetGrayAll(isGray)`  —  文件: `BattleHurtNum.lua.lua`
- `BattleHurtNum.ShowAll()`  —  文件: `BattleHurtNum.lua.lua`
- `BattleHurtNum.ShowBattleSkillTipsAni(bindObject, skillType, skillId, ignoreTimescale)`  —  文件: `BattleHurtNum.lua.lua`
- `BattleHurtNum.ShowBuffWord(bindObject, word, wordType)`  —  文件: `BattleHurtNum.lua.lua`
- `BattleHurtNum.ShowExpression(expressionType, bindObject, playTime)`  —  文件: `BattleHurtNum.lua.lua`
- `BattleHurtNum.ShowHurtNum(hurt_type, num, bindObject, hurtExtraParams)`  —  文件: `BattleHurtNum.lua.lua`
- `BattleHurtNum.ShowPopWord(word, bindObject)`  —  文件: `BattleHurtNum.lua.lua`
- `BattleHurtNum.UpdateNormalHurtVisible()`  —  文件: `BattleHurtNum.lua.lua`

### 模块：`BattleInfoWindow`

- `BattleInfoWindow.InitBtn()`  —  文件: `BattleInfoWindow.lua.lua`
- `BattleInfoWindow.OnClose()`  —  文件: `BattleInfoWindow.lua.lua`
- `BattleInfoWindow.OnInit(bridgeObj)`  —  文件: `BattleInfoWindow.lua.lua`
- `BattleInfoWindow.Quit()`  —  文件: `BattleInfoWindow.lua.lua`
- `BattleInfoWindow.ReInitData()`  —  文件: `BattleInfoWindow.lua.lua`
- `BattleInfoWindow.TouchSwitchBtn(eventContext)`  —  文件: `BattleInfoWindow.lua.lua`
- `BattleInfoWindow.UpdateInfo()`  —  文件: `BattleInfoWindow.lua.lua`
- `BattleInfoWindow.UpdateRatioListBtn(eventContext)`  —  文件: `BattleInfoWindow.lua.lua`
- `BattleInfoWindow.UpdateSetTips(tipsHand, info, value)`  —  文件: `BattleInfoWindow.lua.lua`
- `BattleInfoWindow.UpdateSwitchBtn(btn, value)`  —  文件: `BattleInfoWindow.lua.lua`

### 模块：`BattleLoadingWindow`

- `BattleLoadingWindow.HandleMessage(msgId, para)`  —  文件: `BattleLoadingWindow.lua.lua`
- `BattleLoadingWindow.InitBtn()`  —  文件: `BattleLoadingWindow.lua.lua`
- `BattleLoadingWindow.OnClose()`  —  文件: `BattleLoadingWindow.lua.lua`
- `BattleLoadingWindow.OnHide()`  —  文件: `BattleLoadingWindow.lua.lua`
- `BattleLoadingWindow.OnInit(bridgeObj)`  —  文件: `BattleLoadingWindow.lua.lua`
- `BattleLoadingWindow.OnShown()`  —  文件: `BattleLoadingWindow.lua.lua`
- `BattleLoadingWindow.ReInitData()`  —  文件: `BattleLoadingWindow.lua.lua`
- `BattleLoadingWindow.ShowAnimOut(callback)`  —  文件: `BattleLoadingWindow.lua.lua`
- `BattleLoadingWindow.UpdateInfo()`  —  文件: `BattleLoadingWindow.lua.lua`

### 模块：`BattleManuallySkill`

- `BattleManuallySkill.GetMinHpRangeUnit(atkUnit, isSameSide)`  —  文件: `BattleManuallySkill.lua.lua`
- `BattleManuallySkill.InitLocalVar()`  —  文件: `BattleManuallySkill.lua.lua`
- `BattleManuallySkill.NewSkill(skillId, skillLevel, camp)`  —  文件: `BattleManuallySkill.lua.lua`

### 模块：`BattleMessageBar`

- `BattleMessageBar.BindInfo(unit)`  —  文件: `BattleMessageBar.lua.lua`

### 模块：`BattleMgr`

- `BattleMgr.CloseBattle(isManual, forceClose, closeWindowParam)`  —  文件: `BattleMgr.lua.lua`
- `BattleMgr.GetWaveName(waveIndex)`  —  文件: `BattleMgr.lua.lua`
- `BattleMgr.InitBattle(msg, delayClearScene, isPlayback)`  —  文件: `BattleMgr.lua.lua`
- `BattleMgr.InitLocalVar()`  —  文件: `BattleMgr.lua.lua`
- `BattleMgr.OpenFinishWindow(data)`  —  文件: `BattleMgr.lua.lua`
- `BattleMgr.SaveCompleteData(data)`  —  文件: `BattleMgr.lua.lua`
- `BattleMgr.SendBattleOverMsg(data, rspCallback)`  —  文件: `BattleMgr.lua.lua`
- `BattleMgr.StartBattle(delayClearScene)`  —  文件: `BattleMgr.lua.lua`

### 模块：`BattleNumberWindow`

- `BattleNumberWindow.HandleMessage(msgId, para)`  —  文件: `BattleNumberWindow.lua.lua`
- `BattleNumberWindow.Init()`  —  文件: `BattleNumberWindow.lua.lua`
- `BattleNumberWindow.InitBtn()`  —  文件: `BattleNumberWindow.lua.lua`
- `BattleNumberWindow.InitTips()`  —  文件: `BattleNumberWindow.lua.lua`
- `BattleNumberWindow.OnClose()`  —  文件: `BattleNumberWindow.lua.lua`
- `BattleNumberWindow.OnInit(bridgeObj)`  —  文件: `BattleNumberWindow.lua.lua`

### 模块：`BattleOperation`

- `BattleOperation.AddBurstOperation(skill, camp)`  —  文件: `BattleOperation.lua.lua`
- `BattleOperation.AddManuallyOperation(skill, camp)`  —  文件: `BattleOperation.lua.lua`
- `BattleOperation.ChooseBurstSkill(camp)`  —  文件: `BattleOperation.lua.lua`
- `BattleOperation.ChooseManuallySkill(camp)`  —  文件: `BattleOperation.lua.lua`
- `BattleOperation.Clear()`  —  文件: `BattleOperation.lua.lua`
- `BattleOperation.DealManuallyOperationList()`  —  文件: `BattleOperation.lua.lua`
- `BattleOperation.DealOperationList()`  —  文件: `BattleOperation.lua.lua`
- `BattleOperation.GetAutoSkillConditionSort(camp)`  —  文件: `BattleOperation.lua.lua`
- `BattleOperation.GetPausedBurst()`  —  文件: `BattleOperation.lua.lua`
- `BattleOperation.Init()`  —  文件: `BattleOperation.lua.lua`
- `BattleOperation.InitLocalVar()`  —  文件: `BattleOperation.lua.lua`
- `BattleOperation.SavePausedBurst(burst)`  —  文件: `BattleOperation.lua.lua`

### 模块：`BattlePathFinding`

- `BattlePathFinding.AddCloseIndex(x, y)`  —  文件: `BattlePathFinding.lua.lua`
- `BattlePathFinding.ChangeEmpty(x, y)`  —  文件: `BattlePathFinding.lua.lua`
- `BattlePathFinding.ChangeRed(x, y)`  —  文件: `BattlePathFinding.lua.lua`
- `BattlePathFinding.Clear()`  —  文件: `BattlePathFinding.lua.lua`
- `BattlePathFinding.ClearCachedPath()`  —  文件: `BattlePathFinding.lua.lua`
- `BattlePathFinding.ClearTestGrid()`  —  文件: `BattlePathFinding.lua.lua`
- `BattlePathFinding.CreateTestGrid(contentPane)`  —  文件: `BattlePathFinding.lua.lua`
- `BattlePathFinding.FindPath(startPosition, targetPosition)`  —  文件: `BattlePathFinding.lua.lua`
- `BattlePathFinding.Init(countX, countY)`  —  文件: `BattlePathFinding.lua.lua`
- `BattlePathFinding.RemoveCloseIndex(x, y)`  —  文件: `BattlePathFinding.lua.lua`
- `BattlePathFinding.UpdateTestPath(resultPath)`  —  文件: `BattlePathFinding.lua.lua`

### 模块：`BattlePlayerNumberWindow`

- `BattlePlayerNumberWindow.InitBtn()`  —  文件: `BattlePlayerNumberWindow.lua.lua`
- `BattlePlayerNumberWindow.OnClose()`  —  文件: `BattlePlayerNumberWindow.lua.lua`
- `BattlePlayerNumberWindow.OnInit(bridgeObj)`  —  文件: `BattlePlayerNumberWindow.lua.lua`
- `BattlePlayerNumberWindow.Quit()`  —  文件: `BattlePlayerNumberWindow.lua.lua`
- `BattlePlayerNumberWindow.ReInitData()`  —  文件: `BattlePlayerNumberWindow.lua.lua`
- `BattlePlayerNumberWindow.UpdateInfo()`  —  文件: `BattlePlayerNumberWindow.lua.lua`

### 模块：`BattleRecord`

- `BattleRecord.Init()`  —  文件: `BattleRecord.lua.lua`
- `BattleRecord.SaveBasic(mapId, time)`  —  文件: `BattleRecord.lua.lua`
- `BattleRecord.SaveBuffEffectDisplayList(params)`  —  文件: `BattleRecord.lua.lua`
- `BattleRecord.SaveBuffWordsDisplayList(params)`  —  文件: `BattleRecord.lua.lua`
- `BattleRecord.SaveBulletInit(params)`  —  文件: `BattleRecord.lua.lua`
- `BattleRecord.SaveBulletUpdate(params)`  —  文件: `BattleRecord.lua.lua`
- `BattleRecord.SaveHurtDisplayList(params)`  —  文件: `BattleRecord.lua.lua`
- `BattleRecord.SaveRageDisplayList(params)`  —  文件: `BattleRecord.lua.lua`
- `BattleRecord.SaveRecordFile()`  —  文件: `BattleRecord.lua.lua`
- `BattleRecord.SaveUnitInit(params)`  —  文件: `BattleRecord.lua.lua`
- `BattleRecord.SaveUnitUpdate(params)`  —  文件: `BattleRecord.lua.lua`
- `BattleRecord.SetEnableRecord(enable)`  —  文件: `BattleRecord.lua.lua`

### 模块：`BattleScene`

- `BattleScene.AddBomb(bomb)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.AddBullet(bullet)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.AddBurst(burst)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.AddEnemyTrigger(unit, condition, skillId)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.AddManuallySkill(manuallySkill)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.AddManuallySkillInfo(skillInfo)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.AddPartnerTrigger(unit, condition, skillId)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.AddSkillInfo(skillInfo)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.AddUnit(data, initBattle)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.AddUnitToCampList(unit)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.Clear()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.DealCardBurstStart()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.DealClearTarget(battleUnit)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.DealPreBattle()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetAliveCardByCamp(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetAliveCardUnitListByCamp(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetAliveJobCountByCamp(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetAliveUnitByCamp(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetAliveUnitById(id, camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetAllAliveCardUnitList()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetAllAliveUnit()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetAllGrid()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetAllManuallySkill()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetAllUnit()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetArenaMapId()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetBombByUid(uid)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetBombGlobalIndex()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetBossHaveKOSkill()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetBulletByUid(uid)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetBulletGlobalIndex()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetBurst(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetCampObject(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetGridListByCamp(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetInRangeUnit(centerUnit, rangeType, rangeX, rangeY, isSameSide, direction, directionVector, includeSelf)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetInRangeUnitWithCamp(centerUnit, rangeType, rangeX, rangeY, camp, direction, directionVector, includeSelf)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetInitPosition(posIndex, radiusX, radiusY)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetLeftCampXCount()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetManuallySkill(skillId, camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetManuallySkillByCamp(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetManuallySkillGlobalIndex()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetManuallySkillInfos()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetMapArray()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetMapId()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetMapXCount()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetMapYCount()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetMirrorPos(posIndex)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetNoCoverGrid()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetOverlapTeammate(unit)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetPortalTargetPosition()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetRightCampXCount()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetSkillInfos()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetSortBombList()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetSortBulletList()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetSpace()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetSpeed(startPosition, targetPosition, module, moveFront, needFindPath)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetTempAliveUnitList()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetTempMoveStateAliveUnitList()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetTempSpecialStageAliveUnitList()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUidListByUnitList(unitList)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitBlockCountByTargetUid(targetUid)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitById(id, camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitByUid(uid)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitGlobalIndex()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitListByCamp(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitListByCampDirect(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitListByCampForManuallySkill(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitListByCampForManuallySkill2(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitListByEnemyTrigger(battleUnit, condition)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitListByPartnerTrigger(battleUnit, condition, includeSelf)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitListByTargetUid(targetUid)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitListByUidList(uidList)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.GetUnitListForBuffTips(camp)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.Init()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.InitAreaData()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.InitBase()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.InitBg()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.InitBomb()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.InitBullet()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.InitBurst()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.InitLocalVar()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.InitManuallySkill()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.InitMap()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.InitUI()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.InitUnit()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.IsBattleLoss()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.IsBattleOver()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.IsBattleWin()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.IsBurstTime()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.IsMoveIntoTRAP(moveUnit)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.IsTargetCounter(startUnit, targetUnit)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.IsTargetInRange(centerUnit, target, rangeType, rangeX, rangeY, direction, directionVector)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.LeftUnitDead(battleUnit)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.NeedShowKillEnemyCount()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.PlayBoomShow(show)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.PlayBurstSkill(show, battleUnit)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.PlayDragSkill(isDrag, noRotation)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.RemoveBomb(uid)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.RemoveBullet(uid)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.RemoveEnemyTrigger(unit, condition, skillId)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.RemovePartnerTrigger(unit, condition, skillId)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.RemoveUnit(unit)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.RightUnitDead(battleUnit)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.SetCardBurstTimerUtilPause(isPause)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.Stop(forceClose)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.UpdateBattleOverState()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.UpdateCacheDistance(moveUnit)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.UpdateDisplay()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.UpdateHeadInfo()`  —  文件: `BattleScene.lua.lua`
- `BattleScene.UpdateProcess(curFixedFrame)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.UpdateSkillInfo(skillInfo)`  —  文件: `BattleScene.lua.lua`
- `BattleScene.UpdateSkillStartFrameInfo(camp, frame, burstCardSkillStartFrame)`  —  文件: `BattleScene.lua.lua`

### 模块：`BattleService`

- `BattleService.ChallengeStageReq(reqMsg, rspCallback, errorCallback)`  —  文件: `BattleService.lua.lua`
- `BattleService.DealChallengeStageRsp(msg)`  —  文件: `BattleService.lua.lua`
- `BattleService.DealPrepareBattleRsp(msg)`  —  文件: `BattleService.lua.lua`
- `BattleService.DealSaveStagePrepareInfoRsp(msg)`  —  文件: `BattleService.lua.lua`
- `BattleService.GetBattleRecordReq(battleUid, callback)`  —  文件: `BattleService.lua.lua`
- `BattleService.GetBattleRecordRsp(msg)`  —  文件: `BattleService.lua.lua`
- `BattleService.Init()`  —  文件: `BattleService.lua.lua`
- `BattleService.PrepareBattleReq(params)`  —  文件: `BattleService.lua.lua`
- `BattleService.SaveStagePrepareInfoReq(sceneType, cardUid2Pos, buildUid2Pos, leaderCardId, burstOrderSetting, callback)`  —  文件: `BattleService.lua.lua`

### 模块：`BattleSkillWait`

- `BattleSkillWait.AddSkill(unitUid, skillId, targetUidList, specificCondition, triggerFromUnitUid)`  —  文件: `BattleSkillWait.lua.lua`
- `BattleSkillWait.Clear()`  —  文件: `BattleSkillWait.lua.lua`
- `BattleSkillWait.DealSkillWaitList()`  —  文件: `BattleSkillWait.lua.lua`
- `BattleSkillWait.Init()`  —  文件: `BattleSkillWait.lua.lua`
- `BattleSkillWait.InitLocalVar()`  —  文件: `BattleSkillWait.lua.lua`
- `BattleSkillWait.IsSkillWait(unitUid, skillId)`  —  文件: `BattleSkillWait.lua.lua`
- `BattleSkillWait.RemoveSkillWait(unitUid, skillId)`  —  文件: `BattleSkillWait.lua.lua`

### 模块：`BattleSummonWait`

- `BattleSummonWait.AddSummon(param, delayFrame)`  —  文件: `BattleSummonWait.lua.lua`
- `BattleSummonWait.Clear()`  —  文件: `BattleSummonWait.lua.lua`
- `BattleSummonWait.DealSummonWaitList()`  —  文件: `BattleSummonWait.lua.lua`
- `BattleSummonWait.Init()`  —  文件: `BattleSummonWait.lua.lua`

### 模块：`BattleTransform`

- `BattleTransform.AddTransform(transformWait)`  —  文件: `BattleTransform.lua.lua`
- `BattleTransform.CanTransform(unit)`  —  文件: `BattleTransform.lua.lua`
- `BattleTransform.Clear()`  —  文件: `BattleTransform.lua.lua`
- `BattleTransform.DealTransformWaitList()`  —  文件: `BattleTransform.lua.lua`
- `BattleTransform.Init()`  —  文件: `BattleTransform.lua.lua`
- `BattleTransform.InitLocalVar()`  —  文件: `BattleTransform.lua.lua`
- `BattleTransform.RemoveTransformWait(unitUid)`  —  文件: `BattleTransform.lua.lua`

### 模块：`BattleUIWindow`

- `BattleUIWindow.AddCardBurstCdEffect(unitUid)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.AddCardChosenEffect(unitUid)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.AddCardPlayBurstSkillEffect(unitUid)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.AddHeadToList(unit)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.AutoChooseCardBurst(battleUnit, frame)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.BattleEnd()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.BattleStart()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.BossBuffChange(barInfo)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.BossDie()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.BossEnter(unit)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.BossHpChange(data)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.BossRageChange(value)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ChangeWaveUI()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ChooseBurstCardCallback(chooseCard, chooseCostFrame)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ChooseBurstCardComplete()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ClearSkillDrag()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ClickHead(unitUid)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.CreateOneBuff(data, index, buffList)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.CreateOrUpdateOneSkill(skillId)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.HandleMessage(msgId, para)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.HideBurstEffect(lastState, newState)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.InitBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.InitBurstEffect()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.InitCardList()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.InitScoreInfo()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnClickAutoBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnClickManuallySkillAutoBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnClickSetBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnClickSettingBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnClickSkipBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnClickSpeedBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnClickStopBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnClose()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnDragEnd()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnDragMove()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnDragStart(context, skillId, skill)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnHide()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnInit(bridgeObj)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnPreClose()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.OnShowAnimationEnd()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.PlayBurstCardSkillOverGuide()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.PlayBurstSkillChooseCardGuide()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.PlayBurstSkillChooseCardGuide2()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.PlayBurstSkillChooseCardGuide3()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.PlayBurstSkillGuide()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.PreLoadBattleResource(completeCallback)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ReInitData()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.RemoveCardBurstCdEffect(unitUid)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.RemoveCardChosenEffect(unitUid)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.RemoveCardPlayBurstSkillEffect(unitUid)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ShowBurstChooseCard()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ShowBurstEffect(newState)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ShowEnterAnim(callback)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ShowKillEnemyCount()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ShowPlayBattleOver()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ShowPlayBattleStart()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.ShowPlayWaveStart()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.StartChooseCardTimer()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.StopUpdateShow()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateAutoBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateAutoTips()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateBurstChooseCardList()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateBurstChooseList()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateBurstEffectRed(isActive)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateBurstInfo()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateCard(unitUid, unit, barInfo)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateCardDeadInBurst()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateCardSelectState()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateDamageCount()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateDragPosition()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateHangUpState(close)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateInfo()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateManuallySkillAutoBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateRemainTime()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateScoreInfo()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateSettingUI()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateSkillArea(isInit)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateSkillList()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateSpeed()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateSpeedBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateStopBtn()`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateUIVisibleInBurst(show)`  —  文件: `BattleUIWindow.lua.lua`
- `BattleUIWindow.UpdateWave()`  —  文件: `BattleUIWindow.lua.lua`

### 模块：`BattleUnit`

- `BattleUnit.InitLocalVar()`  —  文件: `BattleUnit.lua.lua`
- `BattleUnit.NewUnit(data)`  —  文件: `BattleUnit.lua.lua`

### 模块：`_全局_`

- `callBack()`  —  文件: `BattleUnit.lua.lua`
- `changeFunc(track, event)`  —  文件: `BattleUnit.lua.lua`
- `dealCardSkill(skillId, level)`  —  文件: `BattleUnit.lua.lua`
- `print_battle()`  —  文件: `BattleMgr.lua.lua`
- `print_server()`  —  文件: `BattleMgr.lua.lua`

### 模块：`burstShowList`

- `burstShowList.itemRenderer(index, item)`  —  文件: `BattleInfoWindow.lua.lua`

### 模块：`dotList`

- `dotList.itemRenderer(index, item)`  —  文件: `BattleUIWindow.lua.lua`

### 模块：`list`

- `list.itemRenderer(index, item)`  —  文件: `BattleAxisWindow.lua.lua`
- `list.itemRenderer(index, item)`  —  文件: `BattleDataWindow.lua.lua`

### 模块：`scoreTag`

- `scoreTag.StartList.itemRenderer(index, item)`  —  文件: `BattleUIWindow.lua.lua`

### 模块：`tipsList`

- `tipsList.itemRenderer(i, gcmp)`  —  文件: `BattleFinishWindow.lua.lua`

### 模块：`trackEntry`

- `trackEntry.completeAction()`  —  文件: `BattleActionDisplay.lua.lua`


## 全局表 / 常量

- `ATTRACT`
- `BATTLE_BUFF_TYPE`
- `BATTLE_BURST_STATE`
- `BATTLE_CAMP_FLAG`
- `BATTLE_CONFIG_ENUM`
- `BATTLE_DEPEND_TYPE`
- `BATTLE_MONSTER_RANK`
- `BATTLE_MOTION_STATE_ENUM`
- `BATTLE_MOTION_STATE_INFO`
- `BATTLE_OPERATION_TYPE`
- `BATTLE_RANGE_TYPE`
- `BATTLE_RES_PATH`
- `BATTLE_SPEED_ENUM`
- `BATTLE_STATE_ENUM`
- `BATTLE_TRANSFORM_CONDITION`
- `BATTLE_UNIT_ELEMENT_TYPE`
- `BATTLE_WIN_CONDITION_TYPE`
- `BLIND`
- `BUFF`
- `BUFF_CONTROL_TYPE`
- `BUFF_DEDUCE_TYPE`
- `BUFF_EFFECT_ID`
- `BUFF_EFFECT_TAG`
- `BUFF_EFFECT_VALUE`
- `BUFF_REMOVE_TYPE`
- `BUFF_SETTLE_TYPE`
- `BUFF_STATE_ENUM`
- `BULLET_TYPE_ENUM`
- `BURST_HURT_NUM_ENUM`
- `BattleAction`
- `BattleActionDisplay`
- `BattleAxisWindow`
- `BattleBackground`
- `BattleBomb`
- `BattleBuff`
- `BattleBuffEffect`
- `BattleBuffMgr`
- `BattleBuffWordType`
- `BattleBullet`
- `BattleBurst`
- `BattleBurstSkill`
- `BattleCamp`
- `BattleChoose`
- `BattleControl`
- `BattleData`
- `BattleDataCount`
- `BattleDataWindow`
- `BattleExpressionCom`
- `BattleFinishFailWindow`
- `BattleFinishWindow`
- `BattleGrid`
- `BattleHurtNum`
- `BattleHurtNumComName`
- `BattleHurtNumType`
- `BattleInfoWindow`
- `BattleLoadingWindow`
- `BattleManuallySkill`
- `BattleMessageBar`
- `BattleMgr`
- `BattleNumberWindow`
- `BattleOperation`
- `BattlePathFinding`
- `BattlePlayerNumberWindow`
- `BattleRecord`
- `BattleScene`
- `BattleService`
- `BattleSkillWait`
- `BattleSummonWait`
- `BattleTransform`
- `BattleUIWindow`
- `BattleUnit`
- `CAMERA_POSITION`
- `CHARM`
- `DATA_TYPE_ENUM`
- `DEAD`
- `DEBUFF`
- `EFFECT_ATTR_CAL_TYPE`
- `EXPRESSION_TYPE`
- `FREEZE`
- `HEAD_STATE_COLOR_TEXT_ID`
- `HEAD_STATE_TEXT_ID`
- `HEAD_TYPE`
- `HIT`
- `HURT_NUM_ENUM`
- `MANUALLY_SKILL_STATE`
- `MONSTER_HEAD_STATE_COLOR_TEXT_ID`
- `MONSTER_HEAD_STATE_INDEX_COLOR_TEXT_ID`
- `PERSIST_BURN`
- `PERSIST_DARK`
- `PERSIST_ICE`
- `PERSIST_LIGHT`
- `PERSIST_WATER`
- `PERSIST_WOOD`
- `PETRIFIED`
- `RestraintAddName`
- `RestraintSubName`
- `SILENT`
- `SKILL_DIRECTION`
- `SKILL_MAIN_TYPE`
- `STUN`
- `TRIGGER_CONDITION`
- `TRIGGER_LIMIT`
- `_allAliveUnit`
- `_allAliveUnitHaveRage`
- `_allBombUid`
- `_allBombUidCopy`
- `_allBulletUid`
- `_allBulletUidCopy`
- `_allBurst`
- `_allBurstByCamp`
- `_allCamp`
- `_allGird`
- `_allManuallySkill`
- `_allUnit`
- `_bombByUid`
- `_bulletByUid`
- `_cachedCardBurstTimerUtilList`
- `_cachedEnemyTriggerCondition`
- `_cachedPartnerTriggerCondition`
- `_gridByCamp`
- `_gridByUid`
- `_manuallySkillByCamp`
- `_manuallySkillByUid`
- `_manuallySkillInfos`
- `_mapArray`
- `_rightDeadUnitCountByRank`
- `_rightUnitCountByRank`
- `_skillInfos`
- `_triggerTrap`
- `_unitByCamp`
- `_unitByUid`
- `angleIndexList`
- `angleListAll`
- `attackPointList`
- `attackSoundList`
- `attackSoundTargetList`
- `attackVoiceList`
- `attackWarningEffectList`
- `attrMap`
- `attrNameList`
- `attrStrList`
- `autoManuallySkillCache`
- `availableUnitList`
- `badgeSuitBuffList`
- `barInfo`
- `battleData`
- `battleHurtNumUrlList`
- `beatBackDis`
- `beatBackPerFrame`
- `blockList`
- `bomb`
- `bossBuffListInfo`
- `btnInfoList`
- `btnList`
- `buff`
- `buffEffectDisplayList`
- `buffEffectParams`
- `buffFromAtk`
- `buffList`
- `buffListInfo`
- `buffParams`
- `buffStateCheck`
- `buffUidList`
- `buffUids`
- `buffWordsDisplayList`
- `bullet`
- `bulletExtraParams`
- `bulletInit`
- `bulletInitList`
- `bulletUpdate`
- `bulletUpdateList`
- `burst`
- `burstCardSkillInfoList`
- `burstCardSkillList`
- `burstChooseCardInfos`
- `burstOperationList`
- `burstSkillInfoList`
- `burstSkillList`
- `cached1035SettleUnitUidList`
- `cachedBuffAttr`
- `cachedBuffControlType`
- `cachedBuffEffect`
- `cachedBuffEffectTag`
- `cachedCardBuffList`
- `cachedChallengeStageRsp`
- `cachedDisplayHurtTips`
- `cachedDistance`
- `cachedForceControlEffectIdList`
- `cachedHandByKey`
- `cachedIsMonsterList`
- `cachedList`
- `cachedPath`
- `cachedSkillLevelUpConfigs`
- `cachedSkillShowDisplayInfos`
- `cachedSummonUids`
- `cachedTargetArray`
- `cachedTargetUid`
- `cachedUnitTypeCountList`
- `campList`
- `campObject`
- `campTable`
- `canChargeUnitUidList`
- `cardHeadRegionList`
- `cardList`
- `cardStates`
- `cards`
- `challengeResultData`
- `challengeTargetInfo`
- `chooseCardConfig`
- `clientTeamNeutral`
- `clientTeamRight`
- `closed`
- `color`
- `configs`
- `containAttributeIdMap`
- `containEffect`
- `controlType`
- `copy`
- `copySortBuffUidList`
- `counter`
- `counterEffectParams`
- `coverRadius`
- `coverdGripMap`
- `curBurstSkillCardList`
- `curSettingList`
- `curSkill`
- `curUnitDataList`
- `data`
- `dataList`
- `dataParam`
- `deadInfoMap`
- `deathInfoList`
- `deathList`
- `delayParams`
- `devourPerFrame`
- `display`
- `displayInfo`
- `displayPosition`
- `drops`
- `effect`
- `effectList`
- `effectModelList`
- `effectTagList`
- `effectTags`
- `embattleInfoMap`
- `endPoints`
- `endPosition`
- `enemyTriggerConditionList`
- `extraParams`
- `fashionList`
- `fearTargetPosition`
- `followPositionUnitUid`
- `fromPos`
- `grid`
- `gridList`
- `headInfo`
- `hurtDisplayList`
- `hurtEffectParams`
- `hurtExtraParams`
- `hurtUidList`
- `iconList`
- `inRangeUnit`
- `inRangeUnitList`
- `initData`
- `jobList`
- `killMonster`
- `leftBtnList`
- `leftSkillDamage`
- `leftSplitDamage`
- `leftUnitDamage`
- `list`
- `listByType`
- `listenerDeduceList`
- `listenerRemoveList`
- `listenerSettleList`
- `m`
- `manuallyOperationList`
- `manuallySkillDamageInfoList`
- `manuallySkillInfoList`
- `manuallySkillList`
- `math_g_value`
- `math_list`
- `minHpInfoMap`
- `modelAnimationList`
- `monsterIdHistory`
- `motionStateList`
- `motion_id`
- `msg`
- `name`
- `nearestPosition`
- `newOpen`
- `object`
- `oneSplitDamage`
- `oneTypeList`
- `open`
- `openMap`
- `operation`
- `oriPosition`
- `otherEffectList`
- `otherSkillList`
- `otherSkillTriggerTable`
- `param`
- `params`
- `partnerTriggerConditionList`
- `passiveSkillLevel`
- `passiveSkillTriggerTable`
- `path`
- `persistEffect`
- `pointObjectList`
- `pos`
- `position`
- `preloadBank`
- `preloadEffect`
- `rageDisplayList`
- `randomSeeds`
- `realTimeAttrList`
- `record`
- `replayBasic`
- `returnList`
- `returnUnitList`
- `rightBtnList`
- `rightSkillDamage`
- `rightUnitDamage`
- `savedAttackSoundList`
- `savedAttackSoundTargetList`
- `savedAttackVoiceList`
- `savedBuffEffectDisplayList`
- `savedBuffList`
- `savedBuffWordsDisplayList`
- `savedBurstCardSkillStartFrame`
- `savedBurstChooseCardInfos`
- `savedConfigPool`
- `savedHurtDisplayList`
- `savedRageDisplayList`
- `savedSkillLevelUpConfig`
- `savedSkillShowConfig`
- `savedSkillShowDisplayAttackList`
- `savedSkillShowId`
- `savedSmallSkillList`
- `savedSubSkillConfig`
- `savedTriggerList`
- `savedTriggerSkillList`
- `savedWarningEffectList`
- `scoreInfo`
- `self`
- `sendMsg`
- `skeletonModelList`
- `skill`
- `skill2Level`
- `skillEffectList`
- `skillIdList`
- `skillInfoList`
- `skillInitList`
- `skillList`
- `skillListById`
- `skillTargetUidList`
- `skillTypeToSort1`
- `skillTypeToSort2`
- `skillUpdateList`
- `skillWaitList`
- `smallSkillInfoList`
- `smallSkillList`
- `sort2List`
- `sortBuffList`
- `sortList`
- `speed`
- `speedList`
- `startPointPositionOff`
- `startPosition`
- `states`
- `summonList`
- `summonParam`
- `summonWaitList`
- `t`
- `targetInfo`
- `targetPosition`
- `targetUnitList`
- `teamState1`
- `teamState2`
- `temp`
- `tempBuffListForTrans`
- `tempBuffUid`
- `tempCardForChoose`
- `tempCardInfos`
- `tempCenterList`
- `tempContainedEffectList`
- `tempContainedEffectTagList`
- `tempEffectCount`
- `tempList`
- `tempUidList`
- `textList`
- `tos`
- `transformWait`
- `transformWaitList`
- `typeList`
- `uidList`
- `uniqueSkillInfoList`
- `uniqueSkillList`
- `unit`
- `unitDamageInfoList`
- `unitElementCountList`
- `unitInfo`
- `unitInit`
- `unitInitList`
- `unitList`
- `unitRecordList`
- `unitTypeCountList`
- `unitUpdate`
- `unitUpdateList`
- `unitWith1127`
- `unitWithout1127`
- `units`
- `usedAngleList`
- `valueList`
- `waitDealCardBurstSkillList`
- `waitEffectAction`
- `waitSoundAction`
- `waitVoiceAction`
- `waitWarningEffectAction`
- `warningEffect`
- `world`
- `worldTestGrid`

---

> 🧠 文档由 `lua_doc_generator.py` 自动生成
