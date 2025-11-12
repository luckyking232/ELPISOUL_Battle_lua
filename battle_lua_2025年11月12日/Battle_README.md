# Lua Scripts Documentation

自动生成于 2025-11-12 22:16:51


## 文件总览

### 📄 `BattleAction.lua.lua`
**主要函数:**
- `BattleAction.InitLocalVar()`
- `BattleAction.DealPreBattle()`
- `BattleAction.DealBuffPre()`
- `BattleAction.DealUnitBasicBuff()`
- `BattleAction.DealStart()`
- `BattleAction.DealStand()`
- `BattleAction.DealTrick()`
- `BattleAction.DealMove()`
- `BattleAction.DealWaitAttack()`
- `BattleAction.DealAttack()`
- `BattleAction.DealAttackOver()`
- `BattleAction.DealDying()`
- `BattleAction.DealDead()`
- `BattleAction.DealRevive()`
- `BattleAction.DealBeatBack()`
- `BattleAction.DealDevour()`
- `BattleAction.DealFear()`
- `BattleAction.DealPortal()`
- `BattleAction.DealSpecial()`
- `BattleAction.DealSpecialEnd()`
- `BattleAction.ForceChangeState()`
- `BattleAction.DealStopAttack()`
- `BattleAction.ClearAttackInfo()`
- `BattleAction.DealStopMove()`
- `BattleAction.DealSummon()`
- `BattleAction.DealHurt()`
- `BattleAction.DealDamageToTreat()`
- `BattleAction.DealRageChange()`
- `BattleAction.DealBuffSettle()`
- `BattleAction.DealBuffRemove()`
- `BattleAction.DealCheckSkill()`
- `BattleAction.DealTriggerPassiveSkill()`
- `BattleAction.DealTriggerBurstSkill()`
- `BattleAction.DealTriggerSkill()`
- `BattleAction.DealUnitSkill()`
- `BattleAction.DealTriggerSkillCondition()`
- `BattleAction.IsIgnoreTargetInRange()`
- `BattleAction.InitBeatBackUnitData()`
- `BattleAction.InitDevourUnitData()`
- `BattleAction.InitFearUnitData()`
- `BattleAction.DealMoveToAttack()`
- `BattleAction.UpdateModelFlipWhenAttack()`
- `BattleAction.UpdateModelTimescale()`

---

### 📄 `BattleActionDisplay.lua.lua`
**主要函数:**
- `BattleActionDisplay.Init()`
- `BattleActionDisplay.ClearAction()`
- `BattleActionDisplay.GetWaitWarningEffectIndex()`
- `BattleActionDisplay.AddWaitDealSound()`
- `BattleActionDisplay.AddWaitDealEffect()`
- `BattleActionDisplay.AddWaitDealVoice()`
- `BattleActionDisplay.AddWaitDealWarningEffect()`
- `BattleActionDisplay.DealWaitAction()`
- `BattleActionDisplay.InitLocalVar()`
- `BattleActionDisplay.PlayStart()`
- `BattleActionDisplay.PlayStand()`
- `BattleActionDisplay.PlayMove()`
- `BattleActionDisplay.PlayWaitAttack()`
- `BattleActionDisplay.GetUnitRotation()`
- `BattleActionDisplay.PlayAttack()`
- `BattleActionDisplay.PlayDead()`
- `BattleActionDisplay.PlayRevive()`
- `BattleActionDisplay.PlayDestroy()`
- `trackEntry.completeAction()`
- `BattleActionDisplay.PlayStun()`
- `BattleActionDisplay.PlayBeatBack()`
- `BattleActionDisplay.PlayDevour()`
- `BattleActionDisplay.PlayFear()`
- `BattleActionDisplay.PlaySpecial()`
- `BattleActionDisplay.PlayPersistCast()`
- `BattleActionDisplay.PlayHurt()`
- `BattleActionDisplay.PlayRandomHit()`
- `BattleActionDisplay.PlayRage()`
- `BattleActionDisplay.PlayBuffWords()`
- `BattleActionDisplay.PlayBuffEffect()`
- `BattleActionDisplay.PlayHitEffect()`
- `BattleActionDisplay.PlayBuffIconRefresh()`
- `BattleActionDisplay.ClearAttackDisplay()`
- `BattleActionDisplay.ClearSkillEffect()`
- `BattleActionDisplay.UpdateModelFlipWhenAttack()`
- `BattleActionDisplay.UpdateModelTimescale()`
- `BattleActionDisplay.UpdateControlDisplay()`
- `BattleActionDisplay.ShowStealthDisplay()`
- `BattleActionDisplay.ShowFreezeDisplay()`
- `BattleActionDisplay.ShowPetrifiedDisplay()`
- `BattleActionDisplay.PlayBeatBackTrapState()`
- `BattleActionDisplay.PlayTransform()`

---

### 📄 `BattleAxisWindow.lua.lua`
**主要函数:**
- `BattleAxisWindow.ReInitData()`
- `BattleAxisWindow.OnInit()`
- `BattleAxisWindow.CreateWaveList()`
- `list.itemRenderer()`
- `BattleAxisWindow.ClickRoundBtn()`
- `BattleAxisWindow.UpdateBattleData()`
- `BattleAxisWindow.IsWin()`
- `BattleAxisWindow.UpdateAll()`
- `BattleAxisWindow.InitTimelineData()`
- `BattleAxisWindow.InitComp()`
- `BattleAxisWindow.UpdateInfo()`
- `BattleAxisWindow.CreateHand()`
- `BattleAxisWindow.CreateHead()`
- `BattleAxisWindow.UpdateHead()`
- `BattleAxisWindow.CreateBurst()`
- `BattleAxisWindow.CreateManuallySkill()`
- `BattleAxisWindow.CreateUniqueSkill()`
- `BattleAxisWindow.CreateBurstCardSkill()`
- `BattleAxisWindow.CreateSmallSkill()`
- `BattleAxisWindow.CreateDeathSkill()`
- `BattleAxisWindow.UpdateHeadVisible()`
- `BattleAxisWindow.InitBtn()`
- `BattleAxisWindow.ClickUniqueSkillBtn()`
- `BattleAxisWindow.ClickSpecialSkillBtn()`
- `BattleAxisWindow.ClickDeathBtn()`
- `BattleAxisWindow.ClickManuallySkillBtn()`
- `BattleAxisWindow.ClickHand()`
- `BattleAxisWindow.ShowSkillTips()`
- `BattleAxisWindow.IsMonster()`
- `BattleAxisWindow.CloseSkillTips()`
- `BattleAxisWindow.GetShowHeadDataList()`
- `BattleAxisWindow.CloseHeadTips()`
- `BattleAxisWindow.OnShown()`
- `BattleAxisWindow.OnHide()`
- `BattleAxisWindow.OnClose()`
- `BattleAxisWindow.HandleMessage()`

---

### 📄 `BattleBackground.lua.lua`
**主要函数:**
- `BattleBackground.Init()`
- `BattleBackground.Clear()`

---

### 📄 `BattleBomb.lua.lua`
**主要函数:**
- `BattleBomb.InitLocalVar()`
- `BattleBomb.NewBomb()`

---

### 📄 `BattleBuff.lua.lua`
**主要函数:**
- `BattleBuff.InitLocalVar()`
- `BattleBuff.NewBuff()`

---

### 📄 `BattleBuffEffect.lua.lua`
**主要函数:**
- `BattleBuffEffect.InitLocalVar()`
- `BattleBuffEffect.NewEffect()`
- `BattleBuffEffect.DealBeAffectedWithEffect()`
- `BattleBuffEffect.GetEffectValue()`

---

### 📄 `BattleBuffMgr.lua.lua`
**主要函数:**
- `BattleBuffMgr.InitLocalVar()`
- `BattleBuffMgr.Init()`
- `BattleBuffMgr.GetForceControlEffectIdList()`
- `BattleBuffMgr.NewBuff()`
- `BattleBuffMgr.AddToBuffList()`
- `BattleBuffMgr.RemoveFromBuffList()`
- `BattleBuffMgr.ClearBuffByBuffId()`
- `BattleBuffMgr.ClearBuffByEffectId()`
- `BattleBuffMgr.ClearAllBuff()`
- `BattleBuffMgr.RegisterSettleListener()`
- `BattleBuffMgr.RegisterDeduceListener()`
- `BattleBuffMgr.RegisterRemoveListener()`
- `BattleBuffMgr.UnRegisterSettleListenerByUnitUid()`
- `BattleBuffMgr.UnRegisterSettleListener()`
- `BattleBuffMgr.UnRegisterDeduceListener()`
- `BattleBuffMgr.UnRegisterRemoveListener()`
- `BattleBuffMgr.RefreshRegisterDeduceListener()`
- `BattleBuffMgr.TriggerRemoveListener()`
- `BattleBuffMgr.TriggerUnitListener()`
- `BattleBuffMgr.TriggerBulletListener()`
- `BattleBuffMgr.TriggerBombListener()`
- `BattleBuffMgr.TriggerCampListener()`
- `BattleBuffMgr.TriggerListener()`
- `BattleBuffMgr.TriggerListenerBuffAdd()`
- `BattleBuffMgr.GetBuffGlobalIndex()`
- `BattleBuffMgr.GetAllBuff()`
- `BattleBuffMgr.GetAllBurstBuff()`
- `BattleBuffMgr.GetAllBulletBuff()`
- `BattleBuffMgr.GetAllBombBuff()`
- `BattleBuffMgr.DealBulletDirectDamage()`
- `BattleBuffMgr.DealBulletFinalDamageAdd()`
- `BattleBuffMgr.AnalysisBuffList()`
- `BattleBuffMgr.GetBuffByUid()`
- `BattleBuffMgr.GetSavedBuffList()`
- `BattleBuffMgr.UpdateAllBuff()`
- `BattleBuffMgr.GetListenerSettleList()`
- `BattleBuffMgr.GetListenerRemoveList()`
- `BattleBuffMgr.GetListenerDeduceList()`
- `BattleBuffMgr.GetBuffValue()`
- `BattleBuffMgr.GetValueById()`
- `BattleBuffMgr.GetValueByCampAndId()`
- `BattleBuffMgr.GetBuffCountByUnitAndTag()`
- `BattleBuffMgr.GetBuffCountByCampAndId()`
- `BattleBuffMgr.GetEffectCountByCampAndTag()`
- `BattleBuffMgr.GetSummonCountByCamp()`
- `BattleBuffMgr.GetAliveUnitCountByCamp()`
- `BattleBuffMgr.UpdateUnitBuffShield()`
- `BattleBuffMgr.GetUnitListContainEffect()`
- `BattleBuffMgr.ContainEffectId()`
- `BattleBuffMgr.GetContainedEffect()`
- `BattleBuffMgr.GetBombContainedEffect()`
- `BattleBuffMgr.GetSettledBuffByUnitAndId()`
- `BattleBuffMgr.GetSettledBuffByUnitAndType()`
- `BattleBuffMgr.GetSettledBuffByUnitAndEffectID()`
- `BattleBuffMgr.GetSettledBuffByUnitAndEffectTag()`
- `BattleBuffMgr.GetSettledBuffByCampAndId()`
- `BattleBuffMgr.GetSettledBuffByCampAndType()`
- `BattleBuffMgr.GetSettledBuffByCampAndEffectID()`
- `BattleBuffMgr.GetSettledBuffByCampAndEffectTag()`
- `BattleBuffMgr.IsContainBuffFromBuffUid()`
- `BattleBuffMgr.IsBuffImmune()`
- `BattleBuffMgr.IsUnitUntreatable()`
- `BattleBuffMgr.IsUnitUnyielding()`
- `BattleBuffMgr.IsUnitImmuneAllHurt()`
- `BattleBuffMgr.IsUnitInvincible()`
- `BattleBuffMgr.IsUnitStealth()`
- `BattleBuffMgr.IsUnitImmuneBuffHurt()`

---

### 📄 `BattleBullet.lua.lua`
**主要函数:**
- `BattleBullet.InitLocalVar()`
- `BattleBullet.NewBullet()`

---

### 📄 `BattleBurst.lua.lua`
**主要函数:**
- `BattleBurst.InitLocalVar()`
- `BattleBurst.NewBurst()`

---

### 📄 `BattleBurstSkill.lua.lua`
**主要函数:**
- `BattleBurstSkill.InitLocalVar()`
- `BattleBurstSkill.NewSkill()`

---

### 📄 `BattleCamp.lua.lua`
**主要函数:**
- `BattleCamp.NewCamp()`
- `BattleCamp.DealCampCharge()`

---

### 📄 `BattleChoose.lua.lua`
**主要函数:**
- `BattleChoose.InitLocalVar()`
- `BattleChoose.GetRangeInfo()`
- `BattleChoose.GetTargetType()`
- `BattleChoose.GetTargetUnitList()`
- `BattleChoose.GetSkillTargetUnitList()`
- `BattleChoose.GetBuffTargetUnitList()`
- `BattleChoose.GetNearestUnit()`
- `BattleChoose.GetUnitFor2621()`
- `BattleChoose.GetUnitForChooseMoveTarget()`
- `BattleChoose.GetUnitListBySide()`
- `BattleChoose.GetTopAtkSpdUnitList()`
- `BattleChoose.GetTopHpUnitList()`
- `BattleChoose.GetMinHpPerUnit()`
- `BattleChoose.GetTopAtkUnitList()`
- `BattleChoose.GetTopMoveSpdUnitList()`
- `BattleChoose.GetTopDefUnitList()`
- `BattleChoose.GetSummonUnit()`
- `BattleChoose.GetNotSummonUnit()`
- `BattleChoose.GetSameCampCardListWithHp()`
- `BattleChoose.GetDyingUnitList()`
- `BattleChoose.GetUnitListByType()`
- `BattleChoose.GetRandomUnitList()`
- `BattleChoose.GetUnitListForUnit10064()`
- `BattleChoose.GetGridByRatio()`
- `BattleChoose.GetBuffMaxOverlayUnreachedCards()`
- `BattleChoose.GetContainEffectIdCards()`
- `BattleChoose.GetUnitListContainEffectTag()`
- `BattleChoose.GetTopBuffEffectTagCountUnitList()`
- `BattleChoose.GetRandomSort()`
- `BattleChoose.GetRandomGridList()`
- `BattleChoose.GetAllSummonByUnit()`
- `BattleChoose.GetAllSummonBySide()`
- `BattleChoose.GetBulletHurtUnitList()`
- `BattleChoose.GetUnitsFor3120()`

---

### 📄 `BattleConst.lua.lua`
_未检测到函数定义_

---

### 📄 `BattleControl.lua.lua`
**主要函数:**
- `BattleControl.InitLocalVar()`
- `BattleControl.Init()`
- `BattleControl.Start()`
- `BattleControl.UpdateProcess()`
- `BattleControl.UpdateProcess_2()`
- `BattleControl.UpdateDisplay()`
- `BattleControl.UniqueSkillPause()`
- `BattleControl.SlowTime()`
- `BattleControl.Pause()`
- `BattleControl.Continue()`
- `BattleControl.Stop()`

---

### 📄 `BattleData.lua.lua`
**主要函数:**
- `BattleData.InitData()`
- `BattleData.GetAllUnitData()`
- `BattleData.SortUnitListInit()`
- `BattleData.GetRandomForChooseGrid()`
- `BattleData.GetRandomForChooseShowDisplay()`
- `BattleData.GetRandomSeed()`
- `BattleData.GetRandomSeed2()`
- `BattleData.GetRandomForAutoSkill()`
- `BattleData.GetRandomForDisplay()`
- `BattleData.IsBattleNoFail()`
- `BattleData.IsBattlePVP()`
- `BattleData.IsGuildTrain()`
- `BattleData.IsEffectSkill()`
- `BattleData.Clear()`
- `BattleData.CacheChallengeStageRsp()`
- `BattleData.ClearCachedChallengeStageRsp()`
- `BattleData.UpdateBattleScore()`
- `BattleData.GetRogueAliveCountByType()`
- `BattleData.GetSkillShowIdFromGroup()`

---

### 📄 `BattleDataCount.lua.lua`
**主要函数:**
- `BattleDataCount.InitLocalVar()`
- `BattleDataCount.Init()`
- `BattleDataCount.PanDingKeZhiBuff()`
- `BattleDataCount.GetSkillHurt()`
- `BattleDataCount.DealBuffEffect()`
- `BattleDataCount.DealSpecialDamageAdd()`
- `BattleDataCount.GetManuallySkillHurt()`

---

### 📄 `BattleDataWindow.lua.lua`
**主要函数:**
- `BattleDataWindow.ReInitData()`
- `BattleDataWindow.OnInit()`
- `BattleDataWindow.CreateWaveList()`
- `list.itemRenderer()`
- `BattleDataWindow.ClickRoundBtn()`
- `BattleDataWindow.UpdateBattleData()`
- `BattleDataWindow.IsWin()`
- `BattleDataWindow.UpdateAll()`
- `BattleDataWindow.InitTextAndBtn()`
- `BattleDataWindow.GetKilledCountByUid()`
- `BattleDataWindow.InitDamageData()`
- `BattleDataWindow.UpdateUnitInfo()`
- `BattleDataWindow.UpdateList()`
- `BattleDataWindow.UpdateOneItem()`
- `BattleDataWindow.UpdateSkillInfo()`
- `BattleDataWindow.CloseWindow()`
- `BattleDataWindow.RefreshBtn()`
- `BattleDataWindow.RefreshSkillBtn()`
- `BattleDataWindow.SwitchData()`
- `BattleDataWindow.OnShown()`
- `BattleDataWindow.OnHide()`
- `BattleDataWindow.OnClose()`
- `BattleDataWindow.HandleMessage()`

---

### 📄 `BattleFinishFailWindow.lua.lua`
**主要函数:**
- `BattleFinishFailWindow.ReInitData()`
- `BattleFinishFailWindow.OnInit()`
- `BattleFinishFailWindow.UpdateInfo()`
- `BattleFinishFailWindow.UpdateResult()`
- `BattleFinishFailWindow.UpdateCardVoice()`
- `BattleFinishFailWindow.InitBtn()`
- `BattleFinishFailWindow.TryAgain()`
- `BattleFinishFailWindow.CloseWindow()`
- `BattleFinishFailWindow.OpenDataWindow()`
- `BattleFinishFailWindow.OpenAxisWindow()`
- `BattleFinishFailWindow.UpdateAutoBtnText()`
- `BattleFinishFailWindow.OnShown()`
- `BattleFinishFailWindow.OnHide()`
- `BattleFinishFailWindow.StopTalk()`
- `BattleFinishFailWindow.OnClose()`
- `BattleFinishFailWindow.HandleMessage()`

---

### 📄 `BattleFinishWindow.lua.lua`
**主要函数:**
- `BattleFinishWindow.ReInitData()`
- `BattleFinishWindow.OnInit()`
- `BattleFinishWindow.UpdateInfo()`
- `BattleFinishWindow.UpdateTarget()`
- `tipsList.itemRenderer()`
- `BattleFinishWindow.UpdateExp()`
- `BattleFinishWindow.UpdateShowLevelUp()`
- `BattleFinishWindow.IsWin()`
- `BattleFinishWindow.IsOver()`
- `BattleFinishWindow.ShowDamage()`
- `BattleFinishWindow.ShowDamageInGuildWar()`
- `BattleFinishWindow.ShowDamageInRaidBoss()`
- `BattleFinishWindow.UpdateResult()`
- `BattleFinishWindow.UpdateSceneType()`
- `BattleFinishWindow.UpdateItem()`
- `BattleFinishWindow.Sort()`
- `BattleFinishWindow.UpdateCardShow()`
- `BattleFinishWindow.InitBtn()`
- `BattleFinishWindow.CloseWindow()`
- `BattleFinishWindow.OpenDataWindow()`
- `BattleFinishWindow.OpenAxisWindow()`
- `BattleFinishWindow.InitText()`
- `BattleFinishWindow.CancelSave()`
- `BattleFinishWindow.UpdateAutoBtnText()`
- `BattleFinishWindow.DelayedCall()`
- `BattleFinishWindow.OnShown()`
- `BattleFinishWindow.OnHide()`
- `BattleFinishWindow.StopTalk()`
- `BattleFinishWindow.OnClose()`
- `BattleFinishWindow.HandleMessage()`

---

### 📄 `BattleGrid.lua.lua`
**主要函数:**
- `BattleGrid.InitLocalVar()`
- `BattleGrid.NewGrid()`

---

### 📄 `BattleHurtNum.lua.lua`
**主要函数:**
- `BattleHurtNum.Init()`
- `BattleHurtNum.UpdateNormalHurtVisible()`
- `BattleHurtNum.ClearPool()`
- `BattleHurtNum.ShowHurtNum()`
- `BattleHurtNum.ShowBuffWord()`
- `BattleHurtNum.ShowPopWord()`
- `BattleHurtNum.ShowExpression()`
- `BattleHurtNum.ShowBattleSkillTipsAni()`
- `BattleHurtNum.SetGrayAll()`
- `BattleHurtNum.HideAll()`
- `BattleHurtNum.ShowAll()`
- `BattleHurtNum.ClearHurtNum()`

---

### 📄 `BattleInfoWindow.lua.lua`
**主要函数:**
- `BattleInfoWindow.ReInitData()`
- `BattleInfoWindow.OnInit()`
- `BattleInfoWindow.UpdateInfo()`
- `BattleInfoWindow.UpdateSetTips()`
- `burstShowList.itemRenderer()`
- `BattleInfoWindow.UpdateRatioListBtn()`
- `BattleInfoWindow.UpdateSwitchBtn()`
- `BattleInfoWindow.TouchSwitchBtn()`
- `BattleInfoWindow.InitBtn()`
- `BattleInfoWindow.Quit()`
- `BattleInfoWindow.OnClose()`

---

### 📄 `BattleLoadingWindow.lua.lua`
**主要函数:**
- `BattleLoadingWindow.ReInitData()`
- `BattleLoadingWindow.OnInit()`
- `BattleLoadingWindow.UpdateInfo()`
- `BattleLoadingWindow.ShowAnimOut()`
- `BattleLoadingWindow.InitBtn()`
- `BattleLoadingWindow.OnShown()`
- `BattleLoadingWindow.OnHide()`
- `BattleLoadingWindow.OnClose()`
- `BattleLoadingWindow.HandleMessage()`

---

### 📄 `BattleManuallySkill.lua.lua`
**主要函数:**
- `BattleManuallySkill.InitLocalVar()`
- `BattleManuallySkill.NewSkill()`
- `BattleManuallySkill.GetMinHpRangeUnit()`

---

### 📄 `BattleMessageBar.lua.lua`
**主要函数:**
- `BattleMessageBar.BindInfo()`

---

### 📄 `BattleMgr.lua.lua`
**主要函数:**
- `print_battle()`
- `print_server()`
- `BattleMgr.InitLocalVar()`
- `BattleMgr.SaveCompleteData()`
- `BattleMgr.InitBattle()`
- `BattleMgr.StartBattle()`
- `BattleMgr.CloseBattle()`
- `BattleMgr.SendBattleOverMsg()`
- `BattleMgr.OpenFinishWindow()`
- `BattleMgr.GetWaveName()`

---

### 📄 `BattleNumberWindow.lua.lua`
**主要函数:**
- `BattleNumberWindow.OnInit()`
- `BattleNumberWindow.Init()`
- `BattleNumberWindow.InitTips()`
- `BattleNumberWindow.InitBtn()`
- `BattleNumberWindow.HandleMessage()`
- `BattleNumberWindow.OnClose()`

---

### 📄 `BattleOperation.lua.lua`
**主要函数:**
- `BattleOperation.InitLocalVar()`
- `BattleOperation.Init()`
- `BattleOperation.SavePausedBurst()`
- `BattleOperation.GetPausedBurst()`
- `BattleOperation.AddBurstOperation()`
- `BattleOperation.AddManuallyOperation()`
- `BattleOperation.DealOperationList()`
- `BattleOperation.ChooseBurstSkill()`
- `BattleOperation.DealManuallyOperationList()`
- `BattleOperation.ChooseManuallySkill()`
- `BattleOperation.GetAutoSkillConditionSort()`
- `BattleOperation.Clear()`

---

### 📄 `BattlePathFinding.lua.lua`
**主要函数:**
- `BattlePathFinding.Init()`
- `BattlePathFinding.AddCloseIndex()`
- `BattlePathFinding.RemoveCloseIndex()`
- `BattlePathFinding.Clear()`
- `BattlePathFinding.FindPath()`
- `BattlePathFinding.ClearCachedPath()`
- `BattlePathFinding.CreateTestGrid()`
- `BattlePathFinding.ClearTestGrid()`
- `BattlePathFinding.ChangeRed()`
- `BattlePathFinding.ChangeEmpty()`
- `BattlePathFinding.UpdateTestPath()`

---

### 📄 `BattlePlayerNumberWindow.lua.lua`
**主要函数:**
- `BattlePlayerNumberWindow.ReInitData()`
- `BattlePlayerNumberWindow.OnInit()`
- `BattlePlayerNumberWindow.UpdateInfo()`
- `BattlePlayerNumberWindow.InitBtn()`
- `BattlePlayerNumberWindow.Quit()`
- `BattlePlayerNumberWindow.OnClose()`

---

### 📄 `BattleRecord.lua.lua`
**主要函数:**
- `BattleRecord.SetEnableRecord()`
- `BattleRecord.Init()`
- `BattleRecord.SaveBasic()`
- `BattleRecord.SaveUnitInit()`
- `BattleRecord.SaveUnitUpdate()`
- `BattleRecord.SaveHurtDisplayList()`
- `BattleRecord.SaveRageDisplayList()`
- `BattleRecord.SaveBuffWordsDisplayList()`
- `BattleRecord.SaveBuffEffectDisplayList()`
- `BattleRecord.SaveBulletInit()`
- `BattleRecord.SaveBulletUpdate()`
- `BattleRecord.SaveRecordFile()`

---

### 📄 `BattleScene.lua.lua`
**主要函数:**
- `BattleScene.InitLocalVar()`
- `BattleScene.Init()`
- `BattleScene.GetMapId()`
- `BattleScene.GetArenaMapId()`
- `BattleScene.InitBase()`
- `BattleScene.InitMap()`
- `BattleScene.InitAreaData()`
- `BattleScene.GetSpace()`
- `BattleScene.GetMapArray()`
- `BattleScene.GetNoCoverGrid()`
- `BattleScene.GetMapXCount()`
- `BattleScene.GetMapYCount()`
- `BattleScene.GetLeftCampXCount()`
- `BattleScene.GetRightCampXCount()`
- `BattleScene.GetInitPosition()`
- `BattleScene.InitBg()`
- `BattleScene.InitUI()`
- `BattleScene.InitBullet()`
- `BattleScene.InitBomb()`
- `BattleScene.InitUnit()`
- `BattleScene.GetMirrorPos()`
- `BattleScene.GetAllGrid()`
- `BattleScene.GetAllUnit()`
- `BattleScene.GetAllAliveUnit()`
- `BattleScene.GetGridListByCamp()`
- `BattleScene.GetAliveJobCountByCamp()`
- `BattleScene.GetAliveCardByCamp()`
- `BattleScene.GetAliveUnitByCamp()`
- `BattleScene.GetUnitListForBuffTips()`
- `BattleScene.GetUnitListByCampForManuallySkill()`
- `BattleScene.GetUnitListByCampForManuallySkill2()`
- `BattleScene.GetUnitListByCamp()`
- `BattleScene.GetBossHaveKOSkill()`
- `BattleScene.GetAliveCardUnitListByCamp()`
- `BattleScene.GetAllAliveCardUnitList()`
- `BattleScene.GetUnitListByCampDirect()`
- `BattleScene.GetUnitByUid()`
- `BattleScene.GetAliveUnitById()`
- `BattleScene.GetUnitById()`
- `BattleScene.GetUnitListByUidList()`
- `BattleScene.GetUidListByUnitList()`
- `BattleScene.AddSkillInfo()`
- `BattleScene.UpdateSkillInfo()`
- `BattleScene.UpdateSkillStartFrameInfo()`
- `BattleScene.GetSkillInfos()`
- `BattleScene.AddManuallySkillInfo()`
- `BattleScene.GetManuallySkillInfos()`
- `BattleScene.AddUnit()`
- `BattleScene.AddUnitToCampList()`
- `BattleScene.RemoveUnit()`
- `BattleScene.AddPartnerTrigger()`
- `BattleScene.RemovePartnerTrigger()`
- `BattleScene.AddEnemyTrigger()`
- `BattleScene.RemoveEnemyTrigger()`
- `BattleScene.GetUnitListByPartnerTrigger()`
- `BattleScene.GetUnitListByEnemyTrigger()`
- `BattleScene.GetUnitGlobalIndex()`
- `BattleScene.LeftUnitDead()`
- `BattleScene.RightUnitDead()`
- `BattleScene.IsBattleWin()`
- `BattleScene.IsBattleLoss()`
- `BattleScene.AddBomb()`
- `BattleScene.RemoveBomb()`
- `BattleScene.GetBombGlobalIndex()`
- `BattleScene.GetBombByUid()`
- `BattleScene.GetSortBombList()`
- `BattleScene.AddBullet()`
- `BattleScene.RemoveBullet()`
- `BattleScene.GetBulletGlobalIndex()`
- `BattleScene.GetBulletByUid()`
- `BattleScene.GetSortBulletList()`
- `BattleScene.InitBurst()`
- `BattleScene.AddBurst()`
- `BattleScene.GetBurst()`
- `BattleScene.GetCampObject()`
- `BattleScene.InitManuallySkill()`
- `BattleScene.AddManuallySkill()`
- `BattleScene.GetManuallySkill()`
- `BattleScene.GetManuallySkillByCamp()`
- `BattleScene.GetAllManuallySkill()`
- `BattleScene.GetManuallySkillGlobalIndex()`
- `BattleScene.DealPreBattle()`
- `BattleScene.GetTempAliveUnitList()`
- `BattleScene.GetTempMoveStateAliveUnitList()`
- `BattleScene.GetTempSpecialStageAliveUnitList()`
- `BattleScene.UpdateProcess()`
- `BattleScene.DealCardBurstStart()`
- `BattleScene.UpdateDisplay()`
- `BattleScene.Stop()`
- `BattleScene.UpdateBattleOverState()`
- `BattleScene.NeedShowKillEnemyCount()`
- `BattleScene.IsBattleOver()`
- `BattleScene.PlayDragSkill()`
- `BattleScene.PlayBoomShow()`
- `BattleScene.PlayBurstSkill()`
- `BattleScene.SetCardBurstTimerUtilPause()`
- `BattleScene.GetUnitListByTargetUid()`
- `BattleScene.GetUnitBlockCountByTargetUid()`
- `BattleScene.UpdateCacheDistance()`
- `BattleScene.GetInRangeUnit()`
- `BattleScene.GetInRangeUnitWithCamp()`
- `BattleScene.IsTargetCounter()`
- `BattleScene.IsTargetInRange()`
- `BattleScene.GetOverlapTeammate()`
- `BattleScene.GetPortalTargetPosition()`
- `BattleScene.DealClearTarget()`
- `BattleScene.IsMoveIntoTRAP()`
- `BattleScene.IsBurstTime()`
- `BattleScene.GetSpeed()`
- `BattleScene.UpdateHeadInfo()`
- `BattleScene.Clear()`

---

### 📄 `BattleScriptList.lua.lua`
_未检测到函数定义_

---

### 📄 `BattleService.lua.lua`
**主要函数:**
- `BattleService.Init()`
- `BattleService.SaveStagePrepareInfoReq()`
- `BattleService.DealSaveStagePrepareInfoRsp()`
- `BattleService.PrepareBattleReq()`
- `BattleService.DealPrepareBattleRsp()`
- `BattleService.ChallengeStageReq()`
- `BattleService.DealChallengeStageRsp()`
- `BattleService.GetBattleRecordReq()`
- `BattleService.GetBattleRecordRsp()`

---

### 📄 `BattleSkillWait.lua.lua`
**主要函数:**
- `BattleSkillWait.InitLocalVar()`
- `BattleSkillWait.Init()`
- `BattleSkillWait.AddSkill()`
- `BattleSkillWait.IsSkillWait()`
- `BattleSkillWait.DealSkillWaitList()`
- `BattleSkillWait.RemoveSkillWait()`
- `BattleSkillWait.Clear()`

---

### 📄 `BattleSummonWait.lua.lua`
**主要函数:**
- `BattleSummonWait.Init()`
- `BattleSummonWait.AddSummon()`
- `BattleSummonWait.DealSummonWaitList()`
- `BattleSummonWait.Clear()`

---

### 📄 `BattleTransform.lua.lua`
**主要函数:**
- `BattleTransform.InitLocalVar()`
- `BattleTransform.Init()`
- `BattleTransform.AddTransform()`
- `BattleTransform.DealTransformWaitList()`
- `BattleTransform.RemoveTransformWait()`
- `BattleTransform.CanTransform()`
- `BattleTransform.Clear()`

---

### 📄 `BattleUIWindow.lua.lua`
**主要函数:**
- `BattleUIWindow.ReInitData()`
- `BattleUIWindow.OnInit()`
- `BattleUIWindow.UpdateHangUpState()`
- `BattleUIWindow.UpdateSpeed()`
- `BattleUIWindow.UpdateInfo()`
- `BattleUIWindow.InitScoreInfo()`
- `scoreTag.StartList.itemRenderer()`
- `BattleUIWindow.UpdateScoreInfo()`
- `BattleUIWindow.UpdateAutoTips()`
- `BattleUIWindow.UpdateDamageCount()`
- `BattleUIWindow.InitBtn()`
- `BattleUIWindow.UpdateBtn()`
- `BattleUIWindow.UpdateRemainTime()`
- `BattleUIWindow.UpdateWave()`
- `BattleUIWindow.ShowEnterAnim()`
- `BattleUIWindow.ChangeWaveUI()`
- `BattleUIWindow.ShowPlayBattleStart()`
- `BattleUIWindow.StopUpdateShow()`
- `BattleUIWindow.ShowPlayBattleOver()`
- `BattleUIWindow.ShowPlayWaveStart()`
- `BattleUIWindow.OnClickSkipBtn()`
- `BattleUIWindow.OnClickSettingBtn()`
- `BattleUIWindow.OnClickSetBtn()`
- `BattleUIWindow.OnClickSpeedBtn()`
- `BattleUIWindow.UpdateSpeedBtn()`
- `BattleUIWindow.OnClickAutoBtn()`
- `BattleUIWindow.UpdateAutoBtn()`
- `BattleUIWindow.OnClickStopBtn()`
- `BattleUIWindow.UpdateStopBtn()`
- `BattleUIWindow.UpdateSettingUI()`
- `BattleUIWindow.OnHide()`
- `BattleUIWindow.BattleStart()`
- `BattleUIWindow.BattleEnd()`
- `BattleUIWindow.InitCardList()`
- `BattleUIWindow.AddHeadToList()`
- `BattleUIWindow.UpdateCard()`
- `dotList.itemRenderer()`
- `BattleUIWindow.AddCardChosenEffect()`
- `BattleUIWindow.RemoveCardChosenEffect()`
- `BattleUIWindow.AddCardPlayBurstSkillEffect()`
- `BattleUIWindow.RemoveCardPlayBurstSkillEffect()`
- `BattleUIWindow.AddCardBurstCdEffect()`
- `BattleUIWindow.RemoveCardBurstCdEffect()`
- `BattleUIWindow.ClickHead()`
- `BattleUIWindow.UpdateCardSelectState()`
- `BattleUIWindow.UpdateSkillArea()`
- `BattleUIWindow.OnClickManuallySkillAutoBtn()`
- `BattleUIWindow.UpdateManuallySkillAutoBtn()`
- `BattleUIWindow.CreateOrUpdateOneSkill()`
- `BattleUIWindow.OnDragStart()`
- `BattleUIWindow.OnDragMove()`
- `BattleUIWindow.OnDragEnd()`
- `BattleUIWindow.UpdateDragPosition()`
- `BattleUIWindow.UpdateSkillList()`
- `BattleUIWindow.ClearSkillDrag()`
- `BattleUIWindow.PlayBurstSkillGuide()`
- `BattleUIWindow.PlayBurstSkillChooseCardGuide()`
- `BattleUIWindow.PlayBurstSkillChooseCardGuide2()`
- `BattleUIWindow.PlayBurstSkillChooseCardGuide3()`
- `BattleUIWindow.PlayBurstCardSkillOverGuide()`
- `BattleUIWindow.InitBurstEffect()`
- `BattleUIWindow.UpdateBurstInfo()`
- `BattleUIWindow.HideBurstEffect()`
- `BattleUIWindow.ShowBurstEffect()`
- `BattleUIWindow.UpdateUIVisibleInBurst()`
- `BattleUIWindow.ShowBurstChooseCard()`
- `BattleUIWindow.UpdateBurstChooseList()`
- `BattleUIWindow.UpdateBurstChooseCardList()`
- `BattleUIWindow.StartChooseCardTimer()`
- `BattleUIWindow.UpdateCardDeadInBurst()`
- `BattleUIWindow.ChooseBurstCardCallback()`
- `BattleUIWindow.AutoChooseCardBurst()`
- `BattleUIWindow.ChooseBurstCardComplete()`
- `BattleUIWindow.UpdateBurstEffectRed()`
- `BattleUIWindow.BossEnter()`
- `BattleUIWindow.BossDie()`
- `BattleUIWindow.BossHpChange()`
- `BattleUIWindow.BossRageChange()`
- `BattleUIWindow.BossBuffChange()`
- `BattleUIWindow.CreateOneBuff()`
- `BattleUIWindow.ShowKillEnemyCount()`
- `BattleUIWindow.PreLoadBattleResource()`
- `BattleUIWindow.OnShowAnimationEnd()`
- `BattleUIWindow.OnPreClose()`
- `BattleUIWindow.OnClose()`
- `BattleUIWindow.HandleMessage()`

---

### 📄 `BattleUnit.lua.lua`
**主要函数:**
- `BattleUnit.InitLocalVar()`
- `BattleUnit.NewUnit()`
- `dealCardSkill()`
- `changeFunc()`
- `callBack()`

---

> 🧠 文档由 `lua_doc_generator.py` 自动生成

