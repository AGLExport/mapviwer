AUTOMAKE_OPTIONS = foreign

ACLOCAL_AMFLAGS = -I m4 ${ACLOCAL_FLAGS}

lib_LTLIBRARIES = libmapcore.la

libmapcore_la_SOURCES = \
sms/lib/smsutil/src/smsutil.c \
sms/lib/smsutil/src/polygon.cpp \
sms/sms-core/SMUtil/pthread_msq.c \
sms/sms-core/SMUtil/SMZlb.c \
sms/sms-core/SMCoreDM/RT/RT_MapLib.c \
sms/sms-core/SMCoreDM/RT/RT_MapRead.c \
sms/sms-core/SMCoreDM/RT/RT_TblMake.c \
sms/sms-core/SMCoreDM/RT/RT_TblMain.c \
sms/sms-core/SMCoreDM/RT/RT_Entrance.c \
sms/sms-core/SMCoreDM/RT/RT_LstMake.c \
sms/sms-core/SMCoreDM/RT/RT_ComLib.c \
sms/sms-core/SMCoreDM/RT/RT_LstMain.c \
sms/sms-core/SMCoreDM/SCRGThread.c \
sms/sms-core/SMCoreDM/RG/RG_GuideCtl.c \
sms/sms-core/SMCoreDM/RG/RG_GuideVoiceBuild_jp.c \
sms/sms-core/SMCoreDM/RG/RG_GuideSim.c \
sms/sms-core/SMCoreDM/RG/RG_Entrance.c \
sms/sms-core/SMCoreDM/RG/RG_GuideNear.c \
sms/sms-core/SMCoreDM/RG/RG_ShareData.c \
sms/sms-core/SMCoreDM/RG/RG_GuideVoiceBuild_en.c \
sms/sms-core/SMCoreDM/RG/RG_GuideVoice.c \
sms/sms-core/SMCoreDM/RG/RG_GuideApi.c \
sms/sms-core/SMCoreDM/SCRTThread.c \
sms/sms-core/SMCoreDAL/SMDALAreaCls.c \
sms/sms-core/SMCoreDAL/SMSDDAL.c \
sms/sms-core/SMCoreDAL/SMCorePoiFavorite.cpp \
sms/sms-core/SMCoreDAL/SMPAL.cpp \
sms/sms-core/SMCoreDAL/SMDALParcel.c \
sms/sms-core/SMCoreDAL/SMCoreDALJniWrapper.cpp \
sms/sms-core/SMCoreDAL/SMDALDownloadAreaMap.c \
sms/sms-core/SMCoreDAL/SMDALSystemInfo.c \
sms/sms-core/SMCoreDAL/SMDAL.c \
sms/sms-core/SMCoreDAL/SMCorePoiHistory.cpp \
sms/sms-core/SMCoreDAL/SMMAL.c \
sms/sms-core/SMCoreDAL/SMCorePoiPoint.cpp \
sms/sms-core/SMCCom/SMCComMappingLikeReg.c \
sms/sms-core/SMCCom/SMCComPkgWhiteList.c \
sms/sms-core/SMCCom/SMCComGemLikeReg.c \
sms/sms-core/SMCCom/SMCComPkgReq.c \
sms/sms-core/SMCCom/SMCComPkgCommon.c \
sms/sms-core/SMCCom/SMCComCmnCtrl.c \
sms/sms-core/SMCCom/SMCComTrafficInfo.c \
sms/sms-core/SMCCom/SMCComMapdatabktReq.c \
sms/sms-core/SMCCom/SMCComPkgList.c \
sms/sms-core/SMCCom/SMCComChatHis.c \
sms/sms-core/SMCCom/SMCComTermReg.c \
sms/sms-core/SMCCom/SMCComUpdDataReq.c \
sms/sms-core/SMCCom/SMCComDriveCheckListReq.c \
sms/sms-core/SMCCom/SMCComGemLikeCncl.c \
sms/sms-core/SMCCom/SMCComMappingRateReg.c \
sms/sms-core/SMCCom/SMCComUserReg.c \
sms/sms-core/SMCCom/SMCComProbepostComp.c \
sms/sms-core/SMCCom/SMCComPasswdAlt.c \
sms/sms-core/SMCCom/SMCComRnameAlt.c \
sms/sms-core/SMCCom/SMCComGemAlt.c \
sms/sms-core/SMCCom/SMCComUserpolicyReq.c \
sms/sms-core/SMCCom/SMCComMappingLikeDel.c \
sms/sms-core/SMCCom/SMCComMappingCommentDel.c \
sms/sms-core/SMCCom/SMCComMessageProcess.c \
sms/sms-core/SMCCom/SMCComProbepostReq.c \
sms/sms-core/SMCCom/SMCComParkingrateReq.c \
sms/sms-core/SMCCom/SMCComTokenReq.c \
sms/sms-core/SMCCom/SMCComPkgChkTampering.c \
sms/sms-core/SMCCom/SMCComMappingAlt.c \
sms/sms-core/SMCCom/SMCComRoomSrch.c \
sms/sms-core/SMCCom/SMCComAWS.c \
sms/sms-core/SMCCom/SMCComChatMsg.c \
sms/sms-core/SMCCom/SMCComMappingReg.c \
sms/sms-core/SMCCom/SMCComUpdDataProgressMng.c \
sms/sms-core/SMCCom/SMCComMessageInbox.c \
sms/sms-core/SMCCom/SMCComUserSrch.c \
sms/sms-core/SMCCom/SMCComUserattrInfo.c \
sms/sms-core/SMCCom/SMCComMemberSrch.c \
sms/sms-core/SMCCom/SMCComGemSearch.c \
sms/sms-core/SMCCom/SMCComDriveCheckReq.c \
sms/sms-core/SMCCom/SMCComAreaInfoList.c \
sms/sms-core/SMCCom/SMCComGemIdSearch.c \
sms/sms-core/SMCCom/SMCComSensorProbepostReq.c \
sms/sms-core/SMCCom/SMCComPkgLock.c \
sms/sms-core/SMCCom/SMCComGroupSearch.c \
sms/sms-core/SMCCom/SMCComNoticeListReq.c \
sms/sms-core/SMCCom/SMCComGemTimelineSearch.c \
sms/sms-core/SMCCom/SMCComBackup.c \
sms/sms-core/SMCCom/SMCComRgnInfoList.c \
sms/sms-core/SMCCom/SMCComMappingDel.c \
sms/sms-core/SMCCom/SMCComOAuthUrlReq.c \
sms/sms-core/SMCCom/SMCComPrjNoReq.c \
sms/sms-core/SMCCom/SMCComGemspotIdSearch.c \
sms/sms-core/SMCCom/SMCComGemLikeReq.c \
sms/sms-core/SMCCom/SMCComGemReg.c \
sms/sms-core/SMCCom/SMCComMappingCommentReq.c \
sms/sms-core/SMCCom/SMCComPkgCodeDel.c \
sms/sms-core/SMCCom/SMCComPosInfoUpdate.c \
sms/sms-core/SMCCom/SMCComMappingCommentReg.c \
sms/sms-core/SMCCom/SMCComDaialogStatusReq.c \
sms/sms-core/SMCCom/SMCComGemCommentDel.c \
sms/sms-core/SMCCom/SMCComPosInfoSearch.c \
sms/sms-core/SMCCom/SMCComNotifyReg.c \
sms/sms-core/SMCCom/SMCComGemCommentAlt.c \
sms/sms-core/SMCCom/SMCComRoomReg.c \
sms/sms-core/SMCCom/SMCComMappingSrch.c \
sms/sms-core/SMCCom/SMCComMappingCommentAlt.c \
sms/sms-core/SMCCom/SMCComProbeReq.c \
sms/sms-core/SMCCom/SMCComGemCommentReq.c \
sms/sms-core/SMCCom/SMCComGemspotKwdSearch.c \
sms/sms-core/SMCCom/SMCComAppconfReq.c \
sms/sms-core/SMCCom/SMCComAppconfReg.c \
sms/sms-core/SMCCom/SMCComPkgCodeReg.c \
sms/sms-core/SMCCom/SMCComMappingHistoryReq.c \
sms/sms-core/SMCCom/SMCComDeviceidReq.c \
sms/sms-core/SMCCom/SMCComAuthReq.c \
sms/sms-core/SMCCom/SMCComStarSrchAlt.c \
sms/sms-core/SMCCom/SMCComMappingRateReq.c \
sms/sms-core/SMCCom/SMCComNoticeReq.c \
sms/sms-core/SMCCom/SMCComMappingIdSrch.c \
sms/sms-core/SMCCom/SMCComDL.c \
sms/sms-core/SMCCom/SMCComAgreeauthReq.c \
sms/sms-core/SMCCom/SMCComChkMapUpd.c \
sms/sms-core/SMCCom/SMCComUser_Srch.c \
sms/sms-core/SMCCom/SMCComUnreadSrch.c \
sms/sms-core/SMCCom/SMCComMappingLikeReq.c \
sms/sms-core/SMCCom/SMCComGemCommentReg.c \
sms/sms-core/SMCCom/SMCComRatingReg.c \
sms/sms-core/SMCCom/SMCComGemDel.c \
sms/sms-core/SMCoreLC/dummy_locator.c \
sms/sms-core/SMCoreSD/SDT/SMCoreSDTDispatch.c \
sms/sms-core/SMCoreSD/SDT/SMCoreSDTThread.c \
sms/sms-core/SMCoreSD/SDT/SMCoreSDT.c \
sms/sms-core/SMCoreSD/SDD/SMCoreSDDDispatch.c \
sms/sms-core/SMCoreSD/SDD/SMCoreSDDThread.c \
sms/sms-core/SMCoreSD/SDD/SMCoreSDD.c \
sms/sms-core/SMCoreSD/SDU/SMCoreSDUThread.c \
sms/sms-core/SMCoreSD/SDU/SMCoreSDUDispatch.c \
sms/sms-core/SMCoreSD/SDU/SMCoreSDU.c \
sms/sms-core/SMCoreSD/SDU/SMCoreSDUJson.c \
sms/sms-core/SMCoreSD/SDU/SMCoreSDCmn.c \
sms/sms-core/SMCoreSD/SDM/SMCoreSDMThread.c \
sms/sms-core/SMCoreSD/SDM/SMCoreSDM.c \
sms/sms-core/SMCoreSD/SDM/SMCoreSDMDispatch.c \
sms/sms-core/SMCorePB/PT/SMCorePT.c \
sms/sms-core/SMCorePB/PT/SMCorePTThread.c \
sms/sms-core/SMCorePB/PM/SMCorePMThread.c \
sms/sms-core/SMCorePB/PM/SMCorePMData.c \
sms/sms-core/SMCorePB/PM/SMCorePM.c \
sms/sms-core/SMCorePB/SMCorePBCmn.c \
sms/sms-core/SMCorePB/PU/SMCorePUUpload.c \
sms/sms-core/SMCorePB/PU/SMCorePUThread.c \
sms/sms-core/SMCorePB/PU/SMCorePU.c \
sms/sms-core/SMCoreMP/SMBkgdAnalyze.cpp \
sms/sms-core/SMCoreMP/MP_Param.c \
sms/sms-core/SMCoreMP/MP_CollisionMesh.cpp \
sms/sms-core/SMCoreMP/SCMPThread.c \
sms/sms-core/SMCoreMP/es1emu/MP_Es1Emulation.c \
sms/sms-core/SMCoreMP/es1emu/MP_Matrix.c \
sms/sms-core/SMCoreMP/es1emu/MP_Shader.c \
sms/sms-core/SMCoreMP/MP_Draw.c \
sms/sms-core/SMCoreMP/MP_Debug.c \
sms/sms-core/SMCoreMP/MP_DrawRoute.c \
sms/sms-core/SMCoreMP/MP_Texture.c \
sms/sms-core/SMCoreMP/MP_DrawMap.cpp \
sms/sms-core/SMCoreMP/SMNameAnalyze.cpp \
sms/sms-core/SMCoreMP/SMRoadShapeAnalyze.cpp \
sms/sms-core/SMCoreMP/MP_Icon.c \
sms/sms-core/SMCoreMP/MP_Font.cpp \
sms/sms-core/SMCoreMP/MP_GL.c \
sms/sms-core/SMCoreMP/MP_FontMng.cpp \
sms/sms-core/SMCoreMP/SMRoadNameAnalyze.cpp \
sms/sms-core/SMCoreMP/SCMPDraw.c \
sms/sms-core/SMCoreMP/SMMarkAnalyze.cpp \
sms/sms-core/SMCoreMP/MP_Png.cpp \
sms/sms-core/SMCoreCMN/SMCoreMem.c \
sms/sms-core/SMCoreCMN/SMCoreLog.c \
sms/sms-core/SMCoreCMN/SMCoreDataHandler.c \
sms/sms-core/SMCoreCMN/SMCoreShareData.c \
sms/sms-core/SMCoreCMN/SMCoreDHThread.c \
sms/sms-core/SMCoreCMN/SMCoreFuncMngConfig.c \
sms/sms-core/SMCoreCMN/SMCoreCmn.c \
sms/sms-core/SMCoreCMN/SMCoreMsq.c \
sms/sms-core/SMCoreCMN/SMCoreFuncMng.c \
sms/sms-core/SMCoreCMN/SMCoreFMThread.c \
sms/sms-core/SMCoreCMN/SMCoreMsg.c \
sms/sms-core/SMCoreCMN/SMCoreDataMng.c \
sms/sms-core/SMCoreCMN/SMCoreThread.c \
sms/sms-core/SMCoreCMN/SMCoreMeshCalc.c \
sms/sms-core/SMCoreCMN/MeshCalc.c \
sms/sms-core/SMCoreDHC/DHC_RingBuffer.c \
sms/sms-core/SMCoreDHC/DHC_Cash.c \
sms/sms-core/SMCoreDHC/DHC_CashAreaCls.c \
sms/sms-core/SMCoreDHC/DHC_MemAlloc.c \
sms/sms-core/SMCoreDHC/DHC_MemMgr.c \
sms/sms-core/SMCComDAL/SMCComDAL.c \
sms/sms-core/SMCoreTR/TRT/SMCoreTRTDispatch.c \
sms/sms-core/SMCoreTR/TRT/SMCoreTRT.c \
sms/sms-core/SMCoreTR/TRT/SMCoreTRTThread.c \
sms/sms-core/SMCoreTR/TR/SMCoreTRPos.c \
sms/sms-core/SMCoreTR/TR/SMCoreTRCom.c \
sms/sms-core/SMCoreTR/TR/SMCoreTRMem.c \
sms/sms-core/SMCoreTR/TR/SMCoreTRCmn.c \
sms/sms-core/SMCoreTR/TR/SMCoreTRCache.c \
sms/sms-core/SMCoreTR/TR/SMCoreTRThread.c \
sms/sms-core/SMCoreTR/TR/SMCoreTR.c \
sms/sms-core/SMCoreTR/TR/SMCoreTRDispatch.c \
sms/sms-core/SMCAL/SMCAL.c \
sms/sms-core/SMCAL/SMCALCmn.c \
sms/sms-core/SMCAL/SMCALLog.c \
sms/sms-core/SMCoreCNF/SMCoreReplanConfig.c \
sms/sms-core/SMCoreCNF/SMCorePositionConfig.c \
sms/sms-core/SMCoreCNF/SMCoreGenreDataConfig.c \
sms/sms-core/SMCoreCNF/SMCoreRoutePlanConfig.c \
sms/sms-core/SMCoreCNF/SMCoreGuideConfig.c \
sms/sms-core/SMCoreCNF/SMCoreRouteCostConfig.c \
sms/sms-core/SMCoreCNF/SMCoreMapDispConfig.c \
sms/sms-core/SMCoreCNF/SMCoreDataManagerConfig.c \
sms/sms-core/SMCoreCNF/SMCoreGyroConfig.c \
sms/sms-core/SMCoreCNF/SMCoreIni.c \
sms/sms-core/SMCoreCNF/SMCoreDemoConfig.c \
sms/sms-core/SMCoreCNF/SMCoreConfig.c \
sms/sms-core/navicore.c \
sms/sms-core/SMCoreRP/RP_RouteManager.c \
sms/sms-core/SMCoreRP/RP_Lib.c \
sms/sms-core/SMCoreRP/SCRMThread.c \
sms/sms-core/SMCoreRP/RM_Entrance.c \
sms/sms-core/SMCoreRP/RM_StateObj.c \
sms/sms-core/SMCoreRP/RP_LinkLevelConvert.c \
sms/sms-core/SMCoreRP/RC/RC_DataAccess.c \
sms/sms-core/SMCoreRP/RC/RC_AreaDiv.c \
sms/sms-core/SMCoreRP/RC/RC_AreaDivTop.c \
sms/sms-core/SMCoreRP/RC/RC_Entrance.c \
sms/sms-core/SMCoreRP/RC/RC_Neighbor.c \
sms/sms-core/SMCoreRP/RC/RC_RouteCalc.c \
sms/sms-core/SMCoreRP/RC/RC_RouteControl.c \
sms/sms-core/SMCoreRP/RC/RC_RouteReg.c \
sms/sms-core/SMCoreRP/RC/RC_RouteMake.c \
sms/sms-core/SMCoreRP/RC/RC_RouteEdit.c \
sms/sms-core/SMCoreRP/RC/RC_NetworkMake.c \
sms/sms-core/SMCoreRP/RC/RC_Area.c \
sms/sms-core/SMCoreRP/RC/RC_Candidate.c \
sms/sms-core/SMCoreRP/RC/RC_LevelProcess.c \
sms/sms-core/SMCoreRP/RC/RC_Heap.c \
sms/sms-core/SMCoreRP/RC/RC_CostCalc.c \
sms/sms-core/SMCoreRP/SCRCThread.c \
sms/sms-core/SMCoreRP/RP_Debug.c \
sms/sms-core/SMCoreRP/RP_MemJack.c \
sms/sms-core/SMCComCMN/SMCComMem.c \
sms/sms-core/SMCComCMN/SMCComCmn.c \
sms/sms-core/SMCComCMN/SMCComLog.c \
sms/sms-core/SMCComCMN/SMCComMd5.c \
sms/lib/include/smsutil/smsutil.h \
sms/lib/include/smsutil/polygon.h \
sms/lib/smsutil/src/smsutil.h \
sms/lib/smsutil/src/polygon.h \
sms/sms-core/SMUtil/SMZlb.h \
sms/sms-core/SMUtil/pthread_msq.h \
sms/sms-core/SMUtil/SMUtilInternal.h \
sms/sms-core/internal/smscorecnf.h \
sms/sms-core/internal/smsutil.h \
sms/sms-core/internal/smsccom.h \
sms/sms-core/internal/smscorelc.h \
sms/sms-core/internal/smstypedef.h \
sms/sms-core/internal/smsccomdal.h \
sms/sms-core/internal/smscorepb.h \
sms/sms-core/internal/smscoredhc.h \
sms/sms-core/internal/smscoresd.h \
sms/sms-core/internal/smscorerp.h \
sms/sms-core/internal/smsccomcmn.h \
sms/sms-core/internal/smscorecmn.h \
sms/sms-core/internal/smscoretr.h \
sms/sms-core/internal/smscal.h \
sms/sms-core/internal/smscoredal.h \
sms/sms-core/internal/smscoremp.h \
sms/sms-core/internal/smsstd.h \
sms/sms-core/internal/smscore.h \
sms/sms-core/internal/smscoredm.h \
sms/sms-core/include/navicore.h \
sms/sms-core/include/smsallinclude.h \
sms/sms-core/include/navicoredefex.h \
sms/sms-core/include/navicoredef.h \
sms/sms-core/SMCoreDM/RT/RT_LstDef.h \
sms/sms-core/SMCoreDM/RT/RT_TblDef.h \
sms/sms-core/SMCoreDM/RT/RT_MapDef.h \
sms/sms-core/SMCoreDM/RT/RT_LibDef.h \
sms/sms-core/SMCoreDM/SMCoreDMApi.h \
sms/sms-core/SMCoreDM/SMCoreDMInternal.h \
sms/sms-core/SMCoreDM/RG/RG_CtlDef.h \
sms/sms-core/SMCoreDM/RG/RG_GuideApi.h \
sms/sms-core/SMCoreDAL/SMCoreDALInternalApi.h \
sms/sms-core/SMCoreDAL/SMDALQuery.h \
sms/sms-core/SMCoreDAL/SMSDDAL.h \
sms/sms-core/SMCoreDAL/SMDAL.h \
sms/sms-core/SMCoreDAL/SMDALDef.h \
sms/sms-core/SMCoreDAL/SMCoreDALApi.h \
sms/sms-core/SMCoreDAL/SMPAL.h \
sms/sms-core/SMCoreDAL/SMCoreDALInternal.h \
sms/sms-core/SMCoreDAL/SMMAL.h \
sms/sms-core/SMCCom/SMCComAppconfReq.h \
sms/sms-core/SMCCom/SMCComGemCommentReq.h \
sms/sms-core/SMCCom/SMCComGemReg.h \
sms/sms-core/SMCCom/SMCComUserSrch.h \
sms/sms-core/SMCCom/SMCComGemAlt.h \
sms/sms-core/SMCCom/SMCComRoomReg.h \
sms/sms-core/SMCCom/SMCComGemspotKwdSearch.h \
sms/sms-core/SMCCom/SMCComDriveCheckListReq.h \
sms/sms-core/SMCCom/SMCComUser_Srch.h \
sms/sms-core/SMCCom/SMCComMappingLikeReq.h \
sms/sms-core/SMCCom/SMCComAWS.h \
sms/sms-core/SMCCom/SMCComMappingHistoryReq.h \
sms/sms-core/SMCCom/SMCComCmnCtrl.h \
sms/sms-core/SMCCom/SMCComBackup.h \
sms/sms-core/SMCCom/SMCComProbeReq.h \
sms/sms-core/SMCCom/SMCComInternal.h \
sms/sms-core/SMCCom/SMCComMappingCommentAlt.h \
sms/sms-core/SMCCom/SMCComUpdDataProgressMng.h \
sms/sms-core/SMCCom/SMCComMemberSrch.h \
sms/sms-core/SMCCom/SMCComNoticeListReq.h \
sms/sms-core/SMCCom/SMCComGemspotIdSearch.h \
sms/sms-core/SMCCom/SMCComChkMapUpd.h \
sms/sms-core/SMCCom/SMCComStarSrchAlt.h \
sms/sms-core/SMCCom/SMCComPkgCodeReg.h \
sms/sms-core/SMCCom/SMCComTermReg.h \
sms/sms-core/SMCCom/SMCComProbepostComp.h \
sms/sms-core/SMCCom/SMCComMessageInbox.h \
sms/sms-core/SMCCom/SMCComMessageProcess.h \
sms/sms-core/SMCCom/SMCComRnameAlt.h \
sms/sms-core/SMCCom/SMCComPkgCommon.h \
sms/sms-core/SMCCom/SMCComUserReg.h \
sms/sms-core/SMCCom/SMCComMappingRateReq.h \
sms/sms-core/SMCCom/SMCComGroupSearch.h \
sms/sms-core/SMCCom/SMCComPosInfoUpdate.h \
sms/sms-core/SMCCom/SMCComMappingCommentReg.h \
sms/sms-core/SMCCom/SMCComProbepostReq.h \
sms/sms-core/SMCCom/SMCComGemLikeReg.h \
sms/sms-core/SMCCom/SMCComRoomSrch.h \
sms/sms-core/SMCCom/SMCComChatHis.h \
sms/sms-core/SMCCom/SMCComPkgCodeDel.h \
sms/sms-core/SMCCom/SMCComOAuthUrlReq.h \
sms/sms-core/SMCCom/SMCComTokenReq.h \
sms/sms-core/SMCCom/SMCComMappingLikeReg.h \
sms/sms-core/SMCCom/SMCComSensorProbepostReq.h \
sms/sms-core/SMCCom/SMCComPkgReq.h \
sms/sms-core/SMCCom/SMCComPkgList.h \
sms/sms-core/SMCCom/SMCComNoticeReq.h \
sms/sms-core/SMCCom/SMCComApi.h \
sms/sms-core/SMCCom/SMCComGemTimelineSearch.h \
sms/sms-core/SMCCom/SMCComMappingCommentDel.h \
sms/sms-core/SMCCom/SMCComChatMsg.h \
sms/sms-core/SMCCom/SMCComGemLikeCncl.h \
sms/sms-core/SMCCom/SMCComUserpolicyReq.h \
sms/sms-core/SMCCom/SMCComAgreeauthReq.h \
sms/sms-core/SMCCom/SMCComAreaInfoList.h \
sms/sms-core/SMCCom/SMCComMappingReg.h \
sms/sms-core/SMCCom/SMCComMappingDel.h \
sms/sms-core/SMCCom/SMCComMappingRateReg.h \
sms/sms-core/SMCCom/SMCComGemSearch.h \
sms/sms-core/SMCCom/SMCComPkgChkTampering.h \
sms/sms-core/SMCCom/SMCComMappingCommentReq.h \
sms/sms-core/SMCCom/SMCComAppconfReg.h \
sms/sms-core/SMCCom/SMCComMapdatabktReq.h \
sms/sms-core/SMCCom/SMCComPosInfoSearch.h \
sms/sms-core/SMCCom/SMCComUserattrInfo.h \
sms/sms-core/SMCCom/SMCComTrafficInfo.h \
sms/sms-core/SMCCom/SMCComUnreadSrch.h \
sms/sms-core/SMCCom/SMCComRgnInfoList.h \
sms/sms-core/SMCCom/SMCComDriveCheckReq.h \
sms/sms-core/SMCCom/SMCComAuthReq.h \
sms/sms-core/SMCCom/SMCComUpdDataReq.h \
sms/sms-core/SMCCom/SMCComPkgLock.h \
sms/sms-core/SMCCom/SMCComPrjNoReq.h \
sms/sms-core/SMCCom/SMCComGemCommentDel.h \
sms/sms-core/SMCCom/SMCComMappingLikeDel.h \
sms/sms-core/SMCCom/SMCComParkingrateReq.h \
sms/sms-core/SMCCom/SMCComDeviceidReq.h \
sms/sms-core/SMCCom/SMCComRatingReg.h \
sms/sms-core/SMCCom/SMCComMappingSrch.h \
sms/sms-core/SMCCom/SMCComMappingIdSrch.h \
sms/sms-core/SMCCom/SMCComPasswdAlt.h \
sms/sms-core/SMCCom/SMCComGemLikeReq.h \
sms/sms-core/SMCCom/SMCComGemCommentAlt.h \
sms/sms-core/SMCCom/SMCComGemCommentReg.h \
sms/sms-core/SMCCom/SMCComGemIdSearch.h \
sms/sms-core/SMCCom/SMCComMappingAlt.h \
sms/sms-core/SMCCom/SMCComDL.h \
sms/sms-core/SMCCom/SMCComPkgWhiteList.h \
sms/sms-core/SMCCom/SMCComDaialogStatusReq.h \
sms/sms-core/SMCCom/SMCComGemDel.h \
sms/sms-core/SMCCom/SMCComNotifyReg.h \
sms/sms-core/SMCoreLC/SMCoreLCApi.h \
sms/sms-core/SMCoreSD/SDT/SMCoreSDTDispatch.h \
sms/sms-core/SMCoreSD/SDT/SMCoreSDT.h \
sms/sms-core/SMCoreSD/SDT/SMCoreSDTThread.h \
sms/sms-core/SMCoreSD/SMCoreSDCmn.h \
sms/sms-core/SMCoreSD/SDD/SMCoreSDD.h \
sms/sms-core/SMCoreSD/SDD/SMCoreSDDDispatch.h \
sms/sms-core/SMCoreSD/SDD/SMCoreSDDThread.h \
sms/sms-core/SMCoreSD/SDU/SMCoreSDU.h \
sms/sms-core/SMCoreSD/SDU/SMCoreSDUThread.h \
sms/sms-core/SMCoreSD/SDU/SMCoreSDUJson.h \
sms/sms-core/SMCoreSD/SDU/SMCoreSDUDispatch.h \
sms/sms-core/SMCoreSD/SDM/SMCoreSDMDispatch.h \
sms/sms-core/SMCoreSD/SDM/SMCoreSDM.h \
sms/sms-core/SMCoreSD/SDM/SMCoreSDMThread.h \
sms/sms-core/SMCoreSD/SMCoreSDApi.h \
sms/sms-core/SMCoreSD/SMCoreSDInternal.h \
sms/sms-core/SMCorePB/SMCorePBCmn.h \
sms/sms-core/SMCorePB/SMCorePBInternal.h \
sms/sms-core/SMCorePB/PT/SMCorePTThread.h \
sms/sms-core/SMCorePB/PT/SMCorePT.h \
sms/sms-core/SMCorePB/PM/SMCorePMData.h \
sms/sms-core/SMCorePB/PM/SMCorePMThread.h \
sms/sms-core/SMCorePB/PM/SMCorePM.h \
sms/sms-core/SMCorePB/SMCorePBApi.h \
sms/sms-core/SMCorePB/PU/SMCorePUThread.h \
sms/sms-core/SMCorePB/PU/SMCorePUUpload.h \
sms/sms-core/SMCorePB/PU/SMCorePU.h \
sms/sms-core/SMCoreMP/MP_Param.h \
sms/sms-core/SMCoreMP/MP_Font.h \
sms/sms-core/SMCoreMP/SMNameAnalyze.h \
sms/sms-core/SMCoreMP/MP_Draw.h \
sms/sms-core/SMCoreMP/MP_Def.h \
sms/sms-core/SMCoreMP/MP_GL.h \
sms/sms-core/SMCoreMP/MP_CollisionMesh.h \
sms/sms-core/SMCoreMP/SMCoreMPApi.h \
sms/sms-core/SMCoreMP/MP_Debug.h \
sms/sms-core/SMCoreMP/SMParcelBasisAnalyze.h \
sms/sms-core/SMCoreMP/es1emu/MP_Es1Emulation.h \
sms/sms-core/SMCoreMP/es1emu/MP_Matrix.h \
sms/sms-core/SMCoreMP/es1emu/MP_Shader.h \
sms/sms-core/SMCoreMP/SMRoadShapeAnalyze.h \
sms/sms-core/SMCoreMP/SMRoadNameAnalyze.h \
sms/sms-core/SMCoreMP/MP_FontMng.h \
sms/sms-core/SMCoreMP/MP_Texture.h \
sms/sms-core/SMCoreMP/SMCommonAnalyzeData.h \
sms/sms-core/SMCoreMP/SMBkgdAnalyze.h \
sms/sms-core/SMCoreMP/MP_Png.h \
sms/sms-core/SMCoreMP/MP_DrawMap.h \
sms/sms-core/SMCoreMP/SMCoreMPInternal.h \
sms/sms-core/SMCoreMP/MP_Icon.h \
sms/sms-core/SMCoreMP/SMMarkAnalyze.h \
sms/sms-core/SMCoreCMN/SMCoreVoiceText.h \
sms/sms-core/SMCoreCMN/SMCoreDHThread.h \
sms/sms-core/SMCoreCMN/SMCoreDataHandler.h \
sms/sms-core/SMCoreCMN/SMCoreMsq.h \
sms/sms-core/SMCoreCMN/SMCoreThread.h \
sms/sms-core/SMCoreCMN/SMCoreMsg.h \
sms/sms-core/SMCoreCMN/SMCoreDef.h \
sms/sms-core/SMCoreCMN/SMCoreCMNApi.h \
sms/sms-core/SMCoreCMN/SMCoreMeshCalc.h \
sms/sms-core/SMCoreCMN/SMCoreMem.h \
sms/sms-core/SMCoreCMN/SMCoreFuncMngConfig.h \
sms/sms-core/SMCoreCMN/SMCoreDataMng.h \
sms/sms-core/SMCoreCMN/SMCoreSMSApiPrm.h \
sms/sms-core/SMCoreCMN/SMCoreShareData.h \
sms/sms-core/SMCoreCMN/SMCoreFMThread.h \
sms/sms-core/SMCoreCMN/SMCoreFuncMng.h \
sms/sms-core/SMCoreCMN/SMCoreCMNInternal.h \
sms/sms-core/SMCoreCMN/SMCoreCmn.h \
sms/sms-core/SMCoreCMN/SMCoreLog.h \
sms/sms-core/SMCoreCMN/MeshCalc.h \
sms/sms-core/SMCoreDHC/DHC_Cash.h \
sms/sms-core/SMCoreDHC/SMCoreDHCInternalApi.h \
sms/sms-core/SMCoreDHC/DHC_MemMgr.h \
sms/sms-core/SMCoreDHC/SMCoreDHCApi.h \
sms/sms-core/SMCoreDHC/SMCoreDHC.h \
sms/sms-core/SMCoreDHC/SMCoreDHCInternal.h \
sms/sms-core/SMCComDAL/SMCComDAL.h \
sms/sms-core/SMCComDAL/SMCComDALInternal.h \
sms/sms-core/SMCoreTR/TRT/SMCoreTRT.h \
sms/sms-core/SMCoreTR/SMCoreTRData.h \
sms/sms-core/SMCoreTR/SMCoreTRDef.h \
sms/sms-core/SMCoreTR/TR/SMCoreTRCache.h \
sms/sms-core/SMCoreTR/TR/SMCoreTRMem.h \
sms/sms-core/SMCoreTR/TR/SMCoreTRCom.h \
sms/sms-core/SMCoreTR/TR/SMCoreTRCmn.h \
sms/sms-core/SMCoreTR/TR/SMCoreTR.h \
sms/sms-core/SMCoreTR/TR/SMCoreTRPos.h \
sms/sms-core/SMCoreTR/SMCoreTRApi.h \
sms/sms-core/SMCoreTR/SMCoreTRInternal.h \
sms/sms-core/SMCAL/SMCALApi.h \
sms/sms-core/SMCAL/SMCALDef.h \
sms/sms-core/SMCAL/SMCAL.h \
sms/sms-core/SMCAL/SMCALLog.h \
sms/sms-core/SMCAL/SMCALInternal.h \
sms/sms-core/SMCAL/SMCALCmn.h \
sms/sms-core/SMCoreCNF/SMCoreConfig.h \
sms/sms-core/SMCoreCNF/SMCoreCNFApi.h \
sms/sms-core/SMCoreCNF/SMCoreIni.h \
sms/sms-core/SMCoreCNF/SMCorePositionConfig.h \
sms/sms-core/SMCoreCNF/SMCoreRoutePlanConfig.h \
sms/sms-core/SMCoreCNF/SMCoreCNFInternal.h \
sms/sms-core/SMCoreCNF/SMCoreGyroConfig.h \
sms/sms-core/SMCoreCNF/SMCoreRouteCostConfig.h \
sms/sms-core/SMCoreCNF/SMCoreDataManagerConfig.h \
sms/sms-core/SMCoreCNF/SMCoreReplanConfig.h \
sms/sms-core/SMCoreCNF/SMCoreMapDispConfig.h \
sms/sms-core/SMCoreCNF/SMCoreDemoConfig.h \
sms/sms-core/SMCoreCNF/SMCoreGuideConfig.h \
sms/sms-core/SMCoreCNF/SMCoreGenreDataConfig.h \
sms/sms-core/SMCoreRP/RP_Network.h \
sms/sms-core/SMCoreRP/SMCoreRPInternal.h \
sms/sms-core/SMCoreRP/SMCoreRPDef.h \
sms/sms-core/SMCoreRP/SMCoreRPApi.h \
sms/sms-core/SMCoreRP/SCRP_Control.h \
sms/sms-core/SMCoreRP/RC/RC_Candidate.h \
sms/sms-core/SMCoreRP/RC/RC_Area.h \
sms/sms-core/SMCoreRP/RC/RC_CostCalc.h \
sms/sms-core/SMCoreRP/SMCoreRP.h \
sms/sms-core/SMCoreRP/SMCoreRPInternalApi.h \
sms/sms-core/SMCoreRP/RP_LinkLevelConvert.h \
sms/sms-core/SMCoreRP/RP_Lib.h \
sms/sms-core/SMCComCMN/SMCComLog.h \
sms/sms-core/SMCComCMN/SMCComCMNApi.h \
sms/sms-core/SMCComCMN/SMCComCMNInternal.h \
sms/sms-core/SMCComCMN/SMCComCmn.h \
sms/sms-core/SMCComCMN/SMCComMem.h \
sms/sms-core/SMCComCMN/SMCComMd5.h


libmapcore_la_LDFLAGS= -shared -fPIC -version-info 0:1:0
libmapcore_la_CPPFLAGS = -fPIC \
        -I$(top_srcdir)/src/sms \
        -I$(top_srcdir)/src/sms/lib/include \
        -I$(top_srcdir)/src/sms/locator/include \
        -I$(top_srcdir)/src/sms/sms-core \
        -I$(top_srcdir)/src/sms/sms-core/include \
        -I$(top_srcdir)/src/sms/sms-core/SMUtil

libmapcore_la_CFLAGS = -fPIC \
        @GLIB_CFLAGS@ \
        @FREETYPE2_CFLAGS@ \
        @WAYLAND_CFLAGS@ \
        @GL_CFLAGS@ \
        @ZLIB_CFLAGS@ \
        @SQLITE3_CFLAGS@ \
        @EXPAT_CFLAGS@ \
        @OPENSSL_CFLAGS@

libmapcore_la_CXXFLAGS = -fPIC \
        @GLIB_CFLAGS@ \
        @FREETYPE2_CFLAGS@ \
        @WAYLAND_CFLAGS@ \
        @GL_CFLAGS@ \
        @ZLIB_CFLAGS@ \
        @SQLITE3_CFLAGS@ \
        @EXPAT_CFLAGS@ \
        @OPENSSL_CFLAGS@

libmapcore_la_LIBADD = \
        @OPENSSL_LIBS@ \
        @GL_LIBS@ \
        @ZLIB_LIBS@ \
        @SQLITE3_LIBS@ \
        @EXPAT_LIBS@

bin_PROGRAMS        = mapview
mapview_SOURCES = \
sms/sms-core/include/navicore.h \
sms/sms-core/include/navicoredefex.h \
sms/sms-core/include/navicoredef.h \
sms/sms-core/SMCoreMP/es1emu/MP_Es1Emulation.h \
sms/sms-core/SMCoreMP/MP_Def.h \
sms/sms-core/SMCoreMP/MP_GL.h \
sms/sms-core/SMUtil/pthread_msq.h \
glview/glview.c \
glview/glview_wayland.c \
glview/ivi-application-protocol.c \
yspng/yspng.cpp \
pthread/pthread_timer.c \
main/navi.c \
main/guide.c \
main/route.c \
main/png.cpp \
main/button.c \
main/HMI_Icon.c \
main/font.cpp \
main/image.c \
glview/glview_local.h \
glview/glview.h \
glview/ivi-application-client-protocol.h \
yspng/yspng.h \
pthread/pthread_timer.h \
main/png.h \
main/font.h \
main/navi.h \
main/HMI_Icon.h \
main/image.h \
LICENSE \
COPYING

mapview_CPPFLAGS = \
        -D_BSD_SOURCE \
        -I$(top_srcdir)/src/sms \
        -I$(top_srcdir)/src/sms/lib/include \
        -I$(top_srcdir)/src/sms/locator/include \
        -I$(top_srcdir)/src/sms/sms-core \
        -I$(top_srcdir)/src/sms/sms-core/include \
        -I$(top_srcdir)/src/sms/sms-core/SMUtil \
        -I$(top_srcdir)/src/glview \
        -I$(top_srcdir)/src/yspng \
        -I$(top_srcdir)/src/pthread

mapview_CFLAGS = \
        @GLIB_CFLAGS@ \
        @FREETYPE2_CFLAGS@ \
        @WAYLAND_CFLAGS@ \
        @GL_CFLAGS@ \
        @ZLIB_CFLAGS@ \
        @SQLITE3_CFLAGS@ \
        @EXPAT_CFLAGS@ \
        @OPENSSL_CFLAGS@

mapview_CXXFLAGS = \
        @GLIB_CFLAGS@ \
        @FREETYPE2_CFLAGS@ \
        @WAYLAND_CFLAGS@ \
        @GL_CFLAGS@ \
        @ZLIB_CFLAGS@ \
        @SQLITE3_CFLAGS@ \
        @EXPAT_CFLAGS@ \
        @OPENSSL_CFLAGS@

mapview_LDADD = \
	-lrt \
	libmapcore.la \
        @GLIB_LIBS@ \
        @FREETYPE2_LIBS@ \
        @WAYLAND_LIBS@ \
        @GL_LIBS@ \
        @ZLIB_LIBS@ \
        @SQLITE3_LIBS@ \
        @EXPAT_LIBS@ \
        @OPENSSL_LIBS@

#



