diff --git a/other/GeneratedAI/AccountAI.py b/other/GeneratedAI/AccountAI.py
new file mode 100644
index 0000000..95f04dc
--- /dev/null
+++ b/other/GeneratedAI/AccountAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class AccountAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('AccountAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/AccountUD.py b/other/GeneratedAI/AccountUD.py
new file mode 100644
index 0000000..0a6d8c2
--- /dev/null
+++ b/other/GeneratedAI/AccountUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class AccountUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('AccountUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/AvatarFriendsManagerUD.py b/other/GeneratedAI/AvatarFriendsManagerUD.py
new file mode 100644
index 0000000..4699a80
--- /dev/null
+++ b/other/GeneratedAI/AvatarFriendsManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class AvatarFriendsManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('AvatarFriendsManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/AwardMakerUD.py b/other/GeneratedAI/AwardMakerUD.py
new file mode 100644
index 0000000..60e43b8
--- /dev/null
+++ b/other/GeneratedAI/AwardMakerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class AwardMakerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('AwardMakerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/BossAI.py b/other/GeneratedAI/BossAI.py
new file mode 100644
index 0000000..7c153ae
--- /dev/null
+++ b/other/GeneratedAI/BossAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class BossAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('BossAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/CentralLoggerAI.py b/other/GeneratedAI/CentralLoggerAI.py
new file mode 100644
index 0000000..42ce86e
--- /dev/null
+++ b/other/GeneratedAI/CentralLoggerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class CentralLoggerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('CentralLoggerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/CentralLoggerUD.py b/other/GeneratedAI/CentralLoggerUD.py
new file mode 100644
index 0000000..b5d2844
--- /dev/null
+++ b/other/GeneratedAI/CentralLoggerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class CentralLoggerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('CentralLoggerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/CodeRedemptionUD.py b/other/GeneratedAI/CodeRedemptionUD.py
new file mode 100644
index 0000000..ea23f16
--- /dev/null
+++ b/other/GeneratedAI/CodeRedemptionUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class CodeRedemptionUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('CodeRedemptionUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/Distributed7StudTableAI.py b/other/GeneratedAI/Distributed7StudTableAI.py
new file mode 100644
index 0000000..d5bce46
--- /dev/null
+++ b/other/GeneratedAI/Distributed7StudTableAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class Distributed7StudTableAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('Distributed7StudTableAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedAnimalAI.py b/other/GeneratedAI/DistributedAnimalAI.py
new file mode 100644
index 0000000..2fb8850
--- /dev/null
+++ b/other/GeneratedAI/DistributedAnimalAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedAnimalAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedAnimalAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedAvatarAI.py b/other/GeneratedAI/DistributedAvatarAI.py
new file mode 100644
index 0000000..eb3b93a
--- /dev/null
+++ b/other/GeneratedAI/DistributedAvatarAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedAvatarAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedAvatarAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedAvatarManagerAI.py b/other/GeneratedAI/DistributedAvatarManagerAI.py
new file mode 100644
index 0000000..f6b8a7e
--- /dev/null
+++ b/other/GeneratedAI/DistributedAvatarManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedAvatarManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedAvatarManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedAvatarManagerUD.py b/other/GeneratedAI/DistributedAvatarManagerUD.py
new file mode 100644
index 0000000..32e547c
--- /dev/null
+++ b/other/GeneratedAI/DistributedAvatarManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedAvatarManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedAvatarManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedAvatarUD.py b/other/GeneratedAI/DistributedAvatarUD.py
new file mode 100644
index 0000000..7130ee7
--- /dev/null
+++ b/other/GeneratedAI/DistributedAvatarUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedAvatarUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedAvatarUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBandMemberAI.py b/other/GeneratedAI/DistributedBandMemberAI.py
new file mode 100644
index 0000000..81d81d1
--- /dev/null
+++ b/other/GeneratedAI/DistributedBandMemberAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBandMemberAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBandMemberAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBankAI.py b/other/GeneratedAI/DistributedBankAI.py
new file mode 100644
index 0000000..cb1b94f
--- /dev/null
+++ b/other/GeneratedAI/DistributedBankAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBankAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBankAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBattleAvatarAI.py b/other/GeneratedAI/DistributedBattleAvatarAI.py
new file mode 100644
index 0000000..36b9fa6
--- /dev/null
+++ b/other/GeneratedAI/DistributedBattleAvatarAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBattleAvatarAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBattleAvatarAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBattleNPCAI.py b/other/GeneratedAI/DistributedBattleNPCAI.py
new file mode 100644
index 0000000..7f9b4a3
--- /dev/null
+++ b/other/GeneratedAI/DistributedBattleNPCAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBattleNPCAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBattleNPCAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBattleableAI.py b/other/GeneratedAI/DistributedBattleableAI.py
new file mode 100644
index 0000000..ef85fc1
--- /dev/null
+++ b/other/GeneratedAI/DistributedBattleableAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBattleableAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBattleableAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBishopsHandTableAI.py b/other/GeneratedAI/DistributedBishopsHandTableAI.py
new file mode 100644
index 0000000..baf0932
--- /dev/null
+++ b/other/GeneratedAI/DistributedBishopsHandTableAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBishopsHandTableAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBishopsHandTableAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBlackPearlSimpleShipAI.py b/other/GeneratedAI/DistributedBlackPearlSimpleShipAI.py
new file mode 100644
index 0000000..5f48d5b
--- /dev/null
+++ b/other/GeneratedAI/DistributedBlackPearlSimpleShipAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBlackPearlSimpleShipAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBlackPearlSimpleShipAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBlackjackTableAI.py b/other/GeneratedAI/DistributedBlackjackTableAI.py
new file mode 100644
index 0000000..f700e3f
--- /dev/null
+++ b/other/GeneratedAI/DistributedBlackjackTableAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBlackjackTableAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBlackjackTableAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBomberZombieAI.py b/other/GeneratedAI/DistributedBomberZombieAI.py
new file mode 100644
index 0000000..be43fd0
--- /dev/null
+++ b/other/GeneratedAI/DistributedBomberZombieAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBomberZombieAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBomberZombieAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBossCreatureAI.py b/other/GeneratedAI/DistributedBossCreatureAI.py
new file mode 100644
index 0000000..551eccb
--- /dev/null
+++ b/other/GeneratedAI/DistributedBossCreatureAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBossCreatureAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBossCreatureAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBossGhostAI.py b/other/GeneratedAI/DistributedBossGhostAI.py
new file mode 100644
index 0000000..a42a7db
--- /dev/null
+++ b/other/GeneratedAI/DistributedBossGhostAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBossGhostAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBossGhostAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBossNavySailorAI.py b/other/GeneratedAI/DistributedBossNavySailorAI.py
new file mode 100644
index 0000000..fa994ca
--- /dev/null
+++ b/other/GeneratedAI/DistributedBossNavySailorAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBossNavySailorAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBossNavySailorAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBossSkeletonAI.py b/other/GeneratedAI/DistributedBossSkeletonAI.py
new file mode 100644
index 0000000..d8d7bfa
--- /dev/null
+++ b/other/GeneratedAI/DistributedBossSkeletonAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBossSkeletonAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBossSkeletonAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBossTownfolkAI.py b/other/GeneratedAI/DistributedBossTownfolkAI.py
new file mode 100644
index 0000000..68b04e8
--- /dev/null
+++ b/other/GeneratedAI/DistributedBossTownfolkAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBossTownfolkAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBossTownfolkAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBossVoodooZombieAI.py b/other/GeneratedAI/DistributedBossVoodooZombieAI.py
new file mode 100644
index 0000000..08815df
--- /dev/null
+++ b/other/GeneratedAI/DistributedBossVoodooZombieAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBossVoodooZombieAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBossVoodooZombieAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBountyHunterAI.py b/other/GeneratedAI/DistributedBountyHunterAI.py
new file mode 100644
index 0000000..0b24e7f
--- /dev/null
+++ b/other/GeneratedAI/DistributedBountyHunterAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBountyHunterAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBountyHunterAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBuildingDoorAI.py b/other/GeneratedAI/DistributedBuildingDoorAI.py
new file mode 100644
index 0000000..3c07abe
--- /dev/null
+++ b/other/GeneratedAI/DistributedBuildingDoorAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBuildingDoorAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBuildingDoorAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedBuriedTreasureAI.py b/other/GeneratedAI/DistributedBuriedTreasureAI.py
new file mode 100644
index 0000000..8f5956d
--- /dev/null
+++ b/other/GeneratedAI/DistributedBuriedTreasureAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedBuriedTreasureAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedBuriedTreasureAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedCDSteeringWheelAI.py b/other/GeneratedAI/DistributedCDSteeringWheelAI.py
new file mode 100644
index 0000000..a89084a
--- /dev/null
+++ b/other/GeneratedAI/DistributedCDSteeringWheelAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedCDSteeringWheelAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedCDSteeringWheelAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedCDSteeringWheelUD.py b/other/GeneratedAI/DistributedCDSteeringWheelUD.py
new file mode 100644
index 0000000..a670834
--- /dev/null
+++ b/other/GeneratedAI/DistributedCDSteeringWheelUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedCDSteeringWheelUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedCDSteeringWheelUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedCameraAI.py b/other/GeneratedAI/DistributedCameraAI.py
new file mode 100644
index 0000000..6d822cd
--- /dev/null
+++ b/other/GeneratedAI/DistributedCameraAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedCameraAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedCameraAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedCannonDefenseEntranceAI.py b/other/GeneratedAI/DistributedCannonDefenseEntranceAI.py
new file mode 100644
index 0000000..4f2ac99
--- /dev/null
+++ b/other/GeneratedAI/DistributedCannonDefenseEntranceAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedCannonDefenseEntranceAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedCannonDefenseEntranceAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedCannonDefenseShipAI.py b/other/GeneratedAI/DistributedCannonDefenseShipAI.py
new file mode 100644
index 0000000..fc4f99d
--- /dev/null
+++ b/other/GeneratedAI/DistributedCannonDefenseShipAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedCannonDefenseShipAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedCannonDefenseShipAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedCapturePointAI.py b/other/GeneratedAI/DistributedCapturePointAI.py
new file mode 100644
index 0000000..06d6fab
--- /dev/null
+++ b/other/GeneratedAI/DistributedCapturePointAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedCapturePointAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedCapturePointAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedCartesianGridAI.py b/other/GeneratedAI/DistributedCartesianGridAI.py
new file mode 100644
index 0000000..ed02e1d
--- /dev/null
+++ b/other/GeneratedAI/DistributedCartesianGridAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedCartesianGridAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedCartesianGridAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedCellDoorAI.py b/other/GeneratedAI/DistributedCellDoorAI.py
new file mode 100644
index 0000000..097f584
--- /dev/null
+++ b/other/GeneratedAI/DistributedCellDoorAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedCellDoorAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedCellDoorAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedChatManagerAI.py b/other/GeneratedAI/DistributedChatManagerAI.py
new file mode 100644
index 0000000..f1beecf
--- /dev/null
+++ b/other/GeneratedAI/DistributedChatManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedChatManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedChatManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedChatManagerUD.py b/other/GeneratedAI/DistributedChatManagerUD.py
new file mode 100644
index 0000000..b3dbfaf
--- /dev/null
+++ b/other/GeneratedAI/DistributedChatManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedChatManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedChatManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedCreatureAI.py b/other/GeneratedAI/DistributedCreatureAI.py
new file mode 100644
index 0000000..36df8aa
--- /dev/null
+++ b/other/GeneratedAI/DistributedCreatureAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedCreatureAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedCreatureAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedCrewMatchManagerAI.py b/other/GeneratedAI/DistributedCrewMatchManagerAI.py
new file mode 100644
index 0000000..680d7a5
--- /dev/null
+++ b/other/GeneratedAI/DistributedCrewMatchManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedCrewMatchManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedCrewMatchManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedCrewMatchManagerUD.py b/other/GeneratedAI/DistributedCrewMatchManagerUD.py
new file mode 100644
index 0000000..062240c
--- /dev/null
+++ b/other/GeneratedAI/DistributedCrewMatchManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedCrewMatchManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedCrewMatchManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedDailyQuestSpotAI.py b/other/GeneratedAI/DistributedDailyQuestSpotAI.py
new file mode 100644
index 0000000..be292d5
--- /dev/null
+++ b/other/GeneratedAI/DistributedDailyQuestSpotAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedDailyQuestSpotAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedDailyQuestSpotAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedDefendWorldAI.py b/other/GeneratedAI/DistributedDefendWorldAI.py
new file mode 100644
index 0000000..8436786
--- /dev/null
+++ b/other/GeneratedAI/DistributedDefendWorldAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedDefendWorldAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedDefendWorldAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedDefenseCannonAI.py b/other/GeneratedAI/DistributedDefenseCannonAI.py
new file mode 100644
index 0000000..8d97fc0
--- /dev/null
+++ b/other/GeneratedAI/DistributedDefenseCannonAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedDefenseCannonAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedDefenseCannonAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedDiceGameAI.py b/other/GeneratedAI/DistributedDiceGameAI.py
new file mode 100644
index 0000000..3df3437
--- /dev/null
+++ b/other/GeneratedAI/DistributedDiceGameAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedDiceGameAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedDiceGameAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedDinghyAI.py b/other/GeneratedAI/DistributedDinghyAI.py
new file mode 100644
index 0000000..2e03ca5
--- /dev/null
+++ b/other/GeneratedAI/DistributedDinghyAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedDinghyAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedDinghyAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedDirectoryAI.py b/other/GeneratedAI/DistributedDirectoryAI.py
new file mode 100644
index 0000000..59977c3
--- /dev/null
+++ b/other/GeneratedAI/DistributedDirectoryAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedDirectoryAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedDirectoryAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedDistrictAI.py b/other/GeneratedAI/DistributedDistrictAI.py
new file mode 100644
index 0000000..24d05de
--- /dev/null
+++ b/other/GeneratedAI/DistributedDistrictAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedDistrictAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedDistrictAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedDistrictUD.py b/other/GeneratedAI/DistributedDistrictUD.py
new file mode 100644
index 0000000..afeb7c9
--- /dev/null
+++ b/other/GeneratedAI/DistributedDistrictUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedDistrictUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedDistrictUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedDoorBaseAI.py b/other/GeneratedAI/DistributedDoorBaseAI.py
new file mode 100644
index 0000000..18637f1
--- /dev/null
+++ b/other/GeneratedAI/DistributedDoorBaseAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedDoorBaseAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedDoorBaseAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedEnemySpawnerAI.py b/other/GeneratedAI/DistributedEnemySpawnerAI.py
new file mode 100644
index 0000000..02ecf05
--- /dev/null
+++ b/other/GeneratedAI/DistributedEnemySpawnerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedEnemySpawnerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedEnemySpawnerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedFishingSpotAI.py b/other/GeneratedAI/DistributedFishingSpotAI.py
new file mode 100644
index 0000000..be04ce8
--- /dev/null
+++ b/other/GeneratedAI/DistributedFishingSpotAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedFishingSpotAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedFishingSpotAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedFlagAI.py b/other/GeneratedAI/DistributedFlagAI.py
new file mode 100644
index 0000000..cd8080b
--- /dev/null
+++ b/other/GeneratedAI/DistributedFlagAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedFlagAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedFlagAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedFlagShopAI.py b/other/GeneratedAI/DistributedFlagShopAI.py
new file mode 100644
index 0000000..1f1819a
--- /dev/null
+++ b/other/GeneratedAI/DistributedFlagShopAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedFlagShopAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedFlagShopAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedFlagShopUD.py b/other/GeneratedAI/DistributedFlagShopUD.py
new file mode 100644
index 0000000..a6bc637
--- /dev/null
+++ b/other/GeneratedAI/DistributedFlagShopUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedFlagShopUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedFlagShopUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedFlagUD.py b/other/GeneratedAI/DistributedFlagUD.py
new file mode 100644
index 0000000..9ee37be
--- /dev/null
+++ b/other/GeneratedAI/DistributedFlagUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedFlagUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedFlagUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedFlagshipAI.py b/other/GeneratedAI/DistributedFlagshipAI.py
new file mode 100644
index 0000000..65833f0
--- /dev/null
+++ b/other/GeneratedAI/DistributedFlagshipAI.py
@@ -0,0 +1,296 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedFlagshipAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedFlagshipAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
+        self.isBoardable = 0
+        self.isExitable = 0
+        self.isFlagShip = 0
+        self.inBoardingPosition = 0
+        self.wishNameState = ''
+        self.cargo = []
+        self.guildIds = []
+        self.numGuilds = 0
+        self.landGrapple = []
+        self.repairCount = 0
+        self.sailsDown = False
+        self.shipRamDamage = 5.0
+        self.rams = []
+
+    def setIsBoardable(self, isBoardable):
+    	self.isBoardable = isBoardable
+
+    def d_setIsBoardable(self, isBoardable):
+    	self.sendUpdate('setIsBoardable', [
+    		isBoardable])
+
+    def b_setIsBoardable(self, isBoardable):
+    	self.setIsBoardable(isBoardable)
+    	self.d_setIsBoardable(isBoardable)
+
+    def getIsBoardable(self):
+    	return self.isBoardable
+
+    def setIsExitable(self, isExitable):
+    	self.isExitable = isExitable
+
+    def d_setIsExitable(self, isExitable):
+    	self.sendUpdate('setIsBoardable', [
+    		isExitable])
+
+    def b_setIsExitable(self, isExitable):
+    	self.setIsExitable(isExitable)
+    	self.d_setIsExitable(isExitable)
+
+    def getIsExitable(self):
+    	return self.isExitable
+
+    def setIsFlagship(self, isFlagShip):
+    	self.isFlagShip = isFlagShip
+
+    def d_setIsFlagship(self, isFlagShip):
+    	self.sendUpdate('setIsFlagship', [
+    		isFlagShip])
+
+    def b_setIsFlagship(self, isFlagShip):
+    	self.setIsFlagship(isFlagShip)
+    	slef.d_setIsFlagship(isFlagShip)
+
+    def getIsFlagship(self):
+    	return self.isFlagShip
+
+    def setSinkTimer(self, time, timestamp):
+    	self.sendUpdate('setSinkTimer', [
+    		time,
+    		timestamp])
+
+    def damage(self, damage, pos, doId, rams):
+    	self.sendUpdate('damage', [damage,
+    		pos,
+    		doId,
+    		rams])
+
+    def setBoardableShipId(self, shipId):
+    	self.sendUpdate('setBoardableShipId', [
+    		shipId])
+
+    def setIsInBoardingPosition(self, inBoardingPosition):
+    	self.inBoardingPosition = inBoardingPosition
+
+    def d_setIsInBoardingPosition(self, inBoardingPosition):
+    	self.sendUpdate('setIsInBoardingPosition', [
+    		inBoardingPosition])
+
+    def b_setIsInBoardingPosition(self, inBoardingPosition):
+    	self.setIsInBoardingPosition(inBoardingPosition)
+    	self.d_setIsInBoardingPosition(inBoardingPosition)
+
+    def getIsInBoardingPosition(self):
+    	return self.inBoardingPosition
+
+    def requestBoard(self, avId):
+    	avId = self.air.getAvatarIdFromSender()
+    	if not avId:
+    		self.notify.warning('%d does not exist!' % avId)
+    		return None
+
+    def d_setMovie(self, todo1, todo2, todo3, todo4, todo5):
+    	pass
+
+    def shipBoarded(self):
+    	self.sendUpdate('shipBoarded', [])
+
+    def leave(self, avId):
+    	self.sendUpdate('leave', [
+    		avId])
+
+    def setDeploy(self, todo1, todo2):
+    	pass
+
+    def requestBoardFlagship(self, avId):
+    	self.sendUpdate('requestBoardFlagship', [
+    		avId])
+
+    def setWishName(self, wishName):
+    	self.sendUpdateToAvatarId(self.air.getAvatarIdFromSender(), 'setWishName', [
+    		wishName])
+
+    def setWishNameState(self, wishNameState):
+    	self.wishNameState = wishNameState
+    	if self.wishNameState == 'OPEN':
+    		pass
+    	elif self.wishNameState == 'CLOSED':
+    		pass
+    	elif self.wishNameState == 'PENDING':
+    		pass
+    	else:
+    		self.notify.error('WishName %s does not exist!' % self.wishNameState)
+
+    def setCargo(self, cargo):
+    	self.cargo = cargo
+
+    def d_setCargo(self, cargo):
+    	self.sendUpdate('setCargo', [
+    		cargo])
+
+    def b_setCargo(self, cargo):
+    	self.setCargo(cargo)
+    	self.d_setCargo(cargo)
+
+    def getCargo(self):
+    	return self.cargo
+
+    def notifyReceivedLoot(self, lootRecieved):
+    	if lootRecieved is None:
+    		return None
+    	else:
+    		self.notify.info('Loot recieved %d' % lootRecieved)
+
+    def setCaptainId(self, captainId):
+    	if captainId:
+    		self.sendUpdate('setCaptainId', [
+    			captainId])
+    	else:
+    		self.notify.warning('DoId %d does not exist' % captainId)
+    		return None
+
+    def setBadge(self, badge, badgeValue):
+    	if badge:
+    		self.sendUpdate('setBadge', [
+    			badge,
+    			badgeValue])
+    	else:
+    		return 0
+
+    def setRespectDeployBarriers(self, todo1, todo2):
+    	pass
+
+    def numGuilds(self, numGuilds):
+    	self.numGuilds = numGuilds
+
+    def getGuilds(self):
+    	return self.numGuilds
+
+    def setGuildId(self, guildId):
+    	if numGuilds == -1:
+    		return None
+    	self.guildIds.append(guildId)
+    	self.numGuilds(self.getGuilds() + 1)
+    	self.sendUpdate('setGuildId', [
+    		guildId])
+
+    def setClientController(self, avId):
+    	avId = self.air.getAvatarIdFromSender()
+    	if not avId:
+    		self.notify.warning('%d does not exist!' % avId)
+    		return None
+    	self.sendUpdate('setClientController', [
+    		avId])
+
+    def sendCrewToIsland(self, crew, posH):
+    	self.crews = self.getGuilds()
+    	if self.crews:
+    		self.sendUpdate('sendCrewToIsland', [
+    			crew,
+    			posH])
+    	else:
+    		pass
+
+    def dropAnchor(self, shipId):
+    	self.notify.debug('%d droped anchor.' % shipId)
+    	self.sendUpdate('dropAnchor', [
+    		shipId])
+
+    def requestSkillEvent(self, todo1, todo2):
+    	pass
+
+    def recordSkillEvent(self, todo1, todo2):
+    	pass
+
+    def sendShipDefeated(self):
+    	self.notify.debug('Ship was defeated!')
+    	self.sendUpdate('sendShipDefeated', [])
+    	self.setSailsDown(sailsDown=True)
+
+    def setLandedGrapples(self, landGrapple):
+    	self.landGrapple = landGrapple
+
+    def d_setLandedGrapples(self, landGrapple):
+    	self.sendUpdate('setLandedGrapples', [
+    		landGrapple])
+
+    def b_setLandedGrapples(self, landGrapple):
+    	self.setLandedGrapples(landGrapple)
+    	self.d_setLandedGrapples(landGrapple)
+
+    def getLandedGrapples(self):
+    	return self.landGrapple
+
+    def swingLocalAvatarToGrappledShip(self, avId):
+    	avId = self.air.getAvatarIdFromSender()
+    	if not avId:
+    		self.notify.warning('%d doesn not exist!')
+    		return None
+    	self.sendUpdate('swingLocalAvatarToGrappledShip', [
+    		avId])
+
+    def setRespawnLocation(self, avId, zoneId):
+    	if zoneId:
+    		avId = self.air.getAvatarIdFromSender()
+    		if not avId:
+    			self.notify.warning('%d does not exist!')
+    			return None
+    		self.sendUpdate('setRespawnLocation', [
+    			avId,
+    			zoneId])
+
+    def setAllRepairCount(self, repairCount):
+    	self.repairCount = repairCount
+
+    def getAllRepairCount(self):
+    	return self.repairCount
+
+    def setRepairCount(self, repairCount):
+    	self.sendUpdate('setRepairCount', [
+    		repairCount])
+    	self.setAllRepairCount(self.getAllRepairCount() + repairCount)
+
+    def setSailsDown(self, sailsDown):
+    	self.sailsDown = sailsDown
+
+    def d_setSailsDown(self, sailsDown):
+    	self.sendUpdate('setSailsDown', [
+    		sailsDown])
+
+    def b_setSailsDown(self, sailsDown):
+    	self.setSailsDown(sailsDown)
+    	self.d_setSailsDown(sailsDown)
+
+    def getSailsDown(self):
+    	return self.sailsDown
+
+    def requestClientAggro(self):
+    	pass
+
+    def setRams(self, rams):
+    	self.rams.append(rams)
+
+    def getRams(self):
+    	for rams in self.rams:
+    		return rams
+
+    def requestShipRam(self, doId, pos, shipId):
+    	if shipId is None:
+    		self.notify.warning('Client tried to request ram when its ship does not exist!')
+    		return None
+    	else:
+    		self.shipRams = self.getRams()
+    		self.useShipRam(pos)
+    		self.damage(self.shipRamDamage, doId, pos, self.shipRams)
+
+    def useShipRam(self, pos):
+    	self.sendUpdate('useShipRam', [
+    		pos])
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedFlamingBarrelAI.py b/other/GeneratedAI/DistributedFlamingBarrelAI.py
new file mode 100644
index 0000000..553d491
--- /dev/null
+++ b/other/GeneratedAI/DistributedFlamingBarrelAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedFlamingBarrelAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedFlamingBarrelAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedFormationAI.py b/other/GeneratedAI/DistributedFormationAI.py
new file mode 100644
index 0000000..2e28824
--- /dev/null
+++ b/other/GeneratedAI/DistributedFormationAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedFormationAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedFormationAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedFortAI.py b/other/GeneratedAI/DistributedFortAI.py
new file mode 100644
index 0000000..75c180f
--- /dev/null
+++ b/other/GeneratedAI/DistributedFortAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedFortAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedFortAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedFortCannonAI.py b/other/GeneratedAI/DistributedFortCannonAI.py
new file mode 100644
index 0000000..43caa4d
--- /dev/null
+++ b/other/GeneratedAI/DistributedFortCannonAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedFortCannonAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedFortCannonAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedGAConnectorAI.py b/other/GeneratedAI/DistributedGAConnectorAI.py
new file mode 100644
index 0000000..da19702
--- /dev/null
+++ b/other/GeneratedAI/DistributedGAConnectorAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedGAConnectorAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedGAConnectorAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedGADoorAI.py b/other/GeneratedAI/DistributedGADoorAI.py
new file mode 100644
index 0000000..6745738
--- /dev/null
+++ b/other/GeneratedAI/DistributedGADoorAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedGADoorAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedGADoorAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedGAInteriorAI.py b/other/GeneratedAI/DistributedGAInteriorAI.py
new file mode 100644
index 0000000..b0c37e9
--- /dev/null
+++ b/other/GeneratedAI/DistributedGAInteriorAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedGAInteriorAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedGAInteriorAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedGATunnelAI.py b/other/GeneratedAI/DistributedGATunnelAI.py
new file mode 100644
index 0000000..8e1d0a8
--- /dev/null
+++ b/other/GeneratedAI/DistributedGATunnelAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedGATunnelAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedGATunnelAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedGameAreaAI.py b/other/GeneratedAI/DistributedGameAreaAI.py
new file mode 100644
index 0000000..37b2a4f
--- /dev/null
+++ b/other/GeneratedAI/DistributedGameAreaAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedGameAreaAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedGameAreaAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedGameStatManagerAI.py b/other/GeneratedAI/DistributedGameStatManagerAI.py
new file mode 100644
index 0000000..a93afa7
--- /dev/null
+++ b/other/GeneratedAI/DistributedGameStatManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedGameStatManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedGameStatManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedGameTableAI.py b/other/GeneratedAI/DistributedGameTableAI.py
new file mode 100644
index 0000000..2b6676e
--- /dev/null
+++ b/other/GeneratedAI/DistributedGameTableAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedGameTableAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedGameTableAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedGhostAI.py b/other/GeneratedAI/DistributedGhostAI.py
new file mode 100644
index 0000000..c8c8b73
--- /dev/null
+++ b/other/GeneratedAI/DistributedGhostAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedGhostAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedGhostAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedGoldReceiptAI.py b/other/GeneratedAI/DistributedGoldReceiptAI.py
new file mode 100644
index 0000000..fc647ed
--- /dev/null
+++ b/other/GeneratedAI/DistributedGoldReceiptAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedGoldReceiptAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedGoldReceiptAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedGoldReceiptUD.py b/other/GeneratedAI/DistributedGoldReceiptUD.py
new file mode 100644
index 0000000..59013de
--- /dev/null
+++ b/other/GeneratedAI/DistributedGoldReceiptUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedGoldReceiptUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedGoldReceiptUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedHoldemTableAI.py b/other/GeneratedAI/DistributedHoldemTableAI.py
new file mode 100644
index 0000000..1e32a65
--- /dev/null
+++ b/other/GeneratedAI/DistributedHoldemTableAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedHoldemTableAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedHoldemTableAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedHolidayBonfireAI.py b/other/GeneratedAI/DistributedHolidayBonfireAI.py
new file mode 100644
index 0000000..63b2b33
--- /dev/null
+++ b/other/GeneratedAI/DistributedHolidayBonfireAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedHolidayBonfireAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedHolidayBonfireAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedHolidayPigAI.py b/other/GeneratedAI/DistributedHolidayPigAI.py
new file mode 100644
index 0000000..7fcad56
--- /dev/null
+++ b/other/GeneratedAI/DistributedHolidayPigAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedHolidayPigAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedHolidayPigAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInstanceBaseAI.py b/other/GeneratedAI/DistributedInstanceBaseAI.py
new file mode 100644
index 0000000..072bd93
--- /dev/null
+++ b/other/GeneratedAI/DistributedInstanceBaseAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInstanceBaseAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInstanceBaseAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInstanceWorldAI.py b/other/GeneratedAI/DistributedInstanceWorldAI.py
new file mode 100644
index 0000000..375d142
--- /dev/null
+++ b/other/GeneratedAI/DistributedInstanceWorldAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInstanceWorldAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInstanceWorldAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInteractiveAI.py b/other/GeneratedAI/DistributedInteractiveAI.py
new file mode 100644
index 0000000..b3a5771
--- /dev/null
+++ b/other/GeneratedAI/DistributedInteractiveAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInteractiveAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInteractiveAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInteractivePropAI.py b/other/GeneratedAI/DistributedInteractivePropAI.py
new file mode 100644
index 0000000..6d6c2aa
--- /dev/null
+++ b/other/GeneratedAI/DistributedInteractivePropAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInteractivePropAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInteractivePropAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInteractiveUD.py b/other/GeneratedAI/DistributedInteractiveUD.py
new file mode 100644
index 0000000..8ec2e0b
--- /dev/null
+++ b/other/GeneratedAI/DistributedInteractiveUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInteractiveUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInteractiveUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInteriorDoorAI.py b/other/GeneratedAI/DistributedInteriorDoorAI.py
new file mode 100644
index 0000000..7efd72d
--- /dev/null
+++ b/other/GeneratedAI/DistributedInteriorDoorAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInteriorDoorAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInteriorDoorAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInvasionDelFuegoAI.py b/other/GeneratedAI/DistributedInvasionDelFuegoAI.py
new file mode 100644
index 0000000..4bfd668
--- /dev/null
+++ b/other/GeneratedAI/DistributedInvasionDelFuegoAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInvasionDelFuegoAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInvasionDelFuegoAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInvasionObjectAI.py b/other/GeneratedAI/DistributedInvasionObjectAI.py
new file mode 100644
index 0000000..8408693
--- /dev/null
+++ b/other/GeneratedAI/DistributedInvasionObjectAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInvasionObjectAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInvasionObjectAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInvasionPortRoyalAI.py b/other/GeneratedAI/DistributedInvasionPortRoyalAI.py
new file mode 100644
index 0000000..339c5ba
--- /dev/null
+++ b/other/GeneratedAI/DistributedInvasionPortRoyalAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInvasionPortRoyalAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInvasionPortRoyalAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInvasionTortugaAI.py b/other/GeneratedAI/DistributedInvasionTortugaAI.py
new file mode 100644
index 0000000..dd8d508
--- /dev/null
+++ b/other/GeneratedAI/DistributedInvasionTortugaAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInvasionTortugaAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInvasionTortugaAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInventoryAI.py b/other/GeneratedAI/DistributedInventoryAI.py
new file mode 100644
index 0000000..b0f0f27
--- /dev/null
+++ b/other/GeneratedAI/DistributedInventoryAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInventoryAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInventoryAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInventoryManagerAI.py b/other/GeneratedAI/DistributedInventoryManagerAI.py
new file mode 100644
index 0000000..cd0c6b2
--- /dev/null
+++ b/other/GeneratedAI/DistributedInventoryManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInventoryManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInventoryManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInventoryManagerUD.py b/other/GeneratedAI/DistributedInventoryManagerUD.py
new file mode 100644
index 0000000..6512537
--- /dev/null
+++ b/other/GeneratedAI/DistributedInventoryManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInventoryManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInventoryManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedInventoryUD.py b/other/GeneratedAI/DistributedInventoryUD.py
new file mode 100644
index 0000000..d48240c
--- /dev/null
+++ b/other/GeneratedAI/DistributedInventoryUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedInventoryUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedInventoryUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedIslandAI.py b/other/GeneratedAI/DistributedIslandAI.py
new file mode 100644
index 0000000..f076949
--- /dev/null
+++ b/other/GeneratedAI/DistributedIslandAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedIslandAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedIslandAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedIslandCannonAI.py b/other/GeneratedAI/DistributedIslandCannonAI.py
new file mode 100644
index 0000000..47870a3
--- /dev/null
+++ b/other/GeneratedAI/DistributedIslandCannonAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedIslandCannonAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedIslandCannonAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedJailInteriorAI.py b/other/GeneratedAI/DistributedJailInteriorAI.py
new file mode 100644
index 0000000..272f316
--- /dev/null
+++ b/other/GeneratedAI/DistributedJailInteriorAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedJailInteriorAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedJailInteriorAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedJollyRogerAI.py b/other/GeneratedAI/DistributedJollyRogerAI.py
new file mode 100644
index 0000000..b396bf3
--- /dev/null
+++ b/other/GeneratedAI/DistributedJollyRogerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedJollyRogerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedJollyRogerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedKillerGhostAI.py b/other/GeneratedAI/DistributedKillerGhostAI.py
new file mode 100644
index 0000000..41c3bac
--- /dev/null
+++ b/other/GeneratedAI/DistributedKillerGhostAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedKillerGhostAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedKillerGhostAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedLiarsDiceAI.py b/other/GeneratedAI/DistributedLiarsDiceAI.py
new file mode 100644
index 0000000..72c1290
--- /dev/null
+++ b/other/GeneratedAI/DistributedLiarsDiceAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedLiarsDiceAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedLiarsDiceAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedLocationManagerAI.py b/other/GeneratedAI/DistributedLocationManagerAI.py
new file mode 100644
index 0000000..c373537
--- /dev/null
+++ b/other/GeneratedAI/DistributedLocationManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedLocationManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedLocationManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedLockAI.py b/other/GeneratedAI/DistributedLockAI.py
new file mode 100644
index 0000000..f70a4a0
--- /dev/null
+++ b/other/GeneratedAI/DistributedLockAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedLockAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedLockAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedLockDoorAI.py b/other/GeneratedAI/DistributedLockDoorAI.py
new file mode 100644
index 0000000..e98fbae
--- /dev/null
+++ b/other/GeneratedAI/DistributedLockDoorAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedLockDoorAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedLockDoorAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedLootContainerAI.py b/other/GeneratedAI/DistributedLootContainerAI.py
new file mode 100644
index 0000000..d138d4d
--- /dev/null
+++ b/other/GeneratedAI/DistributedLootContainerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedLootContainerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedLootContainerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedLootManagerAI.py b/other/GeneratedAI/DistributedLootManagerAI.py
new file mode 100644
index 0000000..a68b629
--- /dev/null
+++ b/other/GeneratedAI/DistributedLootManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedLootManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedLootManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedMainWorldAI.py b/other/GeneratedAI/DistributedMainWorldAI.py
new file mode 100644
index 0000000..ae11e3e
--- /dev/null
+++ b/other/GeneratedAI/DistributedMainWorldAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedMainWorldAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedMainWorldAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedMatchMakerAI.py b/other/GeneratedAI/DistributedMatchMakerAI.py
new file mode 100644
index 0000000..894474f
--- /dev/null
+++ b/other/GeneratedAI/DistributedMatchMakerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedMatchMakerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedMatchMakerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedMatchMakerUD.py b/other/GeneratedAI/DistributedMatchMakerUD.py
new file mode 100644
index 0000000..3f45c53
--- /dev/null
+++ b/other/GeneratedAI/DistributedMatchMakerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedMatchMakerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedMatchMakerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedMovingObjectAI.py b/other/GeneratedAI/DistributedMovingObjectAI.py
new file mode 100644
index 0000000..b2cdaf8
--- /dev/null
+++ b/other/GeneratedAI/DistributedMovingObjectAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedMovingObjectAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedMovingObjectAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedNPCNavySailorAI.py b/other/GeneratedAI/DistributedNPCNavySailorAI.py
new file mode 100644
index 0000000..c4bc683
--- /dev/null
+++ b/other/GeneratedAI/DistributedNPCNavySailorAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedNPCNavySailorAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedNPCNavySailorAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedNPCPirateAI.py b/other/GeneratedAI/DistributedNPCPirateAI.py
new file mode 100644
index 0000000..519a06e
--- /dev/null
+++ b/other/GeneratedAI/DistributedNPCPirateAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedNPCPirateAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedNPCPirateAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedNPCSimpleShipAI.py b/other/GeneratedAI/DistributedNPCSimpleShipAI.py
new file mode 100644
index 0000000..32a8ca1
--- /dev/null
+++ b/other/GeneratedAI/DistributedNPCSimpleShipAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedNPCSimpleShipAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedNPCSimpleShipAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedNPCSkeletonAI.py b/other/GeneratedAI/DistributedNPCSkeletonAI.py
new file mode 100644
index 0000000..6ecbbdc
--- /dev/null
+++ b/other/GeneratedAI/DistributedNPCSkeletonAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedNPCSkeletonAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedNPCSkeletonAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedNPCTownfolkAI.py b/other/GeneratedAI/DistributedNPCTownfolkAI.py
new file mode 100644
index 0000000..7644c09
--- /dev/null
+++ b/other/GeneratedAI/DistributedNPCTownfolkAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedNPCTownfolkAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedNPCTownfolkAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedNPCToyAI.py b/other/GeneratedAI/DistributedNPCToyAI.py
new file mode 100644
index 0000000..09124ad
--- /dev/null
+++ b/other/GeneratedAI/DistributedNPCToyAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedNPCToyAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedNPCToyAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedNodeAI.py b/other/GeneratedAI/DistributedNodeAI.py
new file mode 100644
index 0000000..c4cc290
--- /dev/null
+++ b/other/GeneratedAI/DistributedNodeAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedNodeAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedNodeAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedNodeUD.py b/other/GeneratedAI/DistributedNodeUD.py
new file mode 100644
index 0000000..0a96d76
--- /dev/null
+++ b/other/GeneratedAI/DistributedNodeUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedNodeUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedNodeUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedOceanGridAI.py b/other/GeneratedAI/DistributedOceanGridAI.py
new file mode 100644
index 0000000..88b7a35
--- /dev/null
+++ b/other/GeneratedAI/DistributedOceanGridAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedOceanGridAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedOceanGridAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPCCannonAI.py b/other/GeneratedAI/DistributedPCCannonAI.py
new file mode 100644
index 0000000..4b56159
--- /dev/null
+++ b/other/GeneratedAI/DistributedPCCannonAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPCCannonAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPCCannonAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPCCannonUD.py b/other/GeneratedAI/DistributedPCCannonUD.py
new file mode 100644
index 0000000..cbb123c
--- /dev/null
+++ b/other/GeneratedAI/DistributedPCCannonUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPCCannonUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPCCannonUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPVPBattleAI.py b/other/GeneratedAI/DistributedPVPBattleAI.py
new file mode 100644
index 0000000..fe95f15
--- /dev/null
+++ b/other/GeneratedAI/DistributedPVPBattleAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPVPBattleAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPVPBattleAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPVPInstanceAI.py b/other/GeneratedAI/DistributedPVPInstanceAI.py
new file mode 100644
index 0000000..97ad68c
--- /dev/null
+++ b/other/GeneratedAI/DistributedPVPInstanceAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPVPInstanceAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPVPInstanceAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPVPShipBattleAI.py b/other/GeneratedAI/DistributedPVPShipBattleAI.py
new file mode 100644
index 0000000..c1f543a
--- /dev/null
+++ b/other/GeneratedAI/DistributedPVPShipBattleAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPVPShipBattleAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPVPShipBattleAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPVPTeamBattleAI.py b/other/GeneratedAI/DistributedPVPTeamBattleAI.py
new file mode 100644
index 0000000..9338cff
--- /dev/null
+++ b/other/GeneratedAI/DistributedPVPTeamBattleAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPVPTeamBattleAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPVPTeamBattleAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPirateBandManagerAI.py b/other/GeneratedAI/DistributedPirateBandManagerAI.py
new file mode 100644
index 0000000..4c5097f
--- /dev/null
+++ b/other/GeneratedAI/DistributedPirateBandManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPirateBandManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPirateBandManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPirateProfileMgrAI.py b/other/GeneratedAI/DistributedPirateProfileMgrAI.py
new file mode 100644
index 0000000..814b264
--- /dev/null
+++ b/other/GeneratedAI/DistributedPirateProfileMgrAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPirateProfileMgrAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPirateProfileMgrAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPiratesTutorialAI.py b/other/GeneratedAI/DistributedPiratesTutorialAI.py
new file mode 100644
index 0000000..5da9d98
--- /dev/null
+++ b/other/GeneratedAI/DistributedPiratesTutorialAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPiratesTutorialAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPiratesTutorialAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPiratesTutorialWorldAI.py b/other/GeneratedAI/DistributedPiratesTutorialWorldAI.py
new file mode 100644
index 0000000..2fe104e
--- /dev/null
+++ b/other/GeneratedAI/DistributedPiratesTutorialWorldAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPiratesTutorialWorldAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPiratesTutorialWorldAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPlayerAI.py b/other/GeneratedAI/DistributedPlayerAI.py
new file mode 100644
index 0000000..6dc8bcd
--- /dev/null
+++ b/other/GeneratedAI/DistributedPlayerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPlayerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPlayerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPlayerFishingShipAI.py b/other/GeneratedAI/DistributedPlayerFishingShipAI.py
new file mode 100644
index 0000000..9567e52
--- /dev/null
+++ b/other/GeneratedAI/DistributedPlayerFishingShipAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPlayerFishingShipAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPlayerFishingShipAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPlayerPirateAI.py b/other/GeneratedAI/DistributedPlayerPirateAI.py
new file mode 100644
index 0000000..1a3e8b4
--- /dev/null
+++ b/other/GeneratedAI/DistributedPlayerPirateAI.py
@@ -0,0 +1,62 @@
+from otp.avatar.DistributedPlayerAI import DistributedPlayerAI
+from direct.directnotify import DirectNotifyGlobal
+from pirates.pirate.HumanDNA import HumanDNA
+
+class DistributedPlayerPirateAI(DistributedPlayerAI, HumanDNA):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPlayerPirateAI')
+
+    def __init__(self, air):
+        DistributedPlayer.__init__(self, air)
+        HumanDNA.__init__(self)
+        self.parentingRules = ('', '')
+        self.avatarType = (0, 0, 0, 0)
+        self.hp = 0
+        self.maxhp = 0
+
+    def generate(self):
+    	DistributedPlayerAI.generate(self)
+
+    def announceGenerate(self):
+    	DistributedPlayerAI.announceGenerate(self)
+
+    def setParentingRules(self, rule1, rule2):
+    	self.parentingRules = (rule1, rule2)
+
+    def setAvatarType(self, avatarType):
+    	self.avatarType = avatarType
+
+    def d_setAvatarType(self, avatarType):
+    	self.sendUpdate('setAvatarType', [
+    		avatarType])
+
+    def b_setAvatarType(self, avatarType):
+    	self.setAvatarType(avatarType)
+    	self.d_setAvatarType(avatarType)
+
+    def getAvatarType(self):
+    	return self.avatarType
+
+    def cueRegenerate(self):
+    	if self.hp >= self.maxhp:
+    		self.notify.warning('The avatars hp level is greater or equal to their max hp!')
+    		return None
+
+    	if self.hp < self.maxHp:
+    		pass
+
+    def submitErrorLog(self, errorLog):
+    	pass
+
+    def requestBodyShapeTranslation(self, bodyTranslation):
+    	self.sendUpdate('requestBodyShapeTranslation', [
+    		bodyTranslation])
+
+    def setInInvasion(self, isInvasion):
+    	self.sendUpdate('setInInvasion', [
+    		isInvasion])
+
+    def disable(self):
+    	DistributedPlayerAI.disable(self)
+
+    def delete(self):
+    	DistributedPlayerAI.delete(self)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPlayerPirateUD.py b/other/GeneratedAI/DistributedPlayerPirateUD.py
new file mode 100644
index 0000000..0fbba00
--- /dev/null
+++ b/other/GeneratedAI/DistributedPlayerPirateUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPlayerPirateUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPlayerPirateUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPlayerSeizeableShipAI.py b/other/GeneratedAI/DistributedPlayerSeizeableShipAI.py
new file mode 100644
index 0000000..585cdf5
--- /dev/null
+++ b/other/GeneratedAI/DistributedPlayerSeizeableShipAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPlayerSeizeableShipAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPlayerSeizeableShipAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPlayerSimpleShipAI.py b/other/GeneratedAI/DistributedPlayerSimpleShipAI.py
new file mode 100644
index 0000000..9450c8e
--- /dev/null
+++ b/other/GeneratedAI/DistributedPlayerSimpleShipAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPlayerSimpleShipAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPlayerSimpleShipAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPlayerSimpleShipUD.py b/other/GeneratedAI/DistributedPlayerSimpleShipUD.py
new file mode 100644
index 0000000..529e0d7
--- /dev/null
+++ b/other/GeneratedAI/DistributedPlayerSimpleShipUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPlayerSimpleShipUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPlayerSimpleShipUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPokerTableAI.py b/other/GeneratedAI/DistributedPokerTableAI.py
new file mode 100644
index 0000000..4df83b1
--- /dev/null
+++ b/other/GeneratedAI/DistributedPokerTableAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPokerTableAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPokerTableAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPopulationTrackerAI.py b/other/GeneratedAI/DistributedPopulationTrackerAI.py
new file mode 100644
index 0000000..b5c5968
--- /dev/null
+++ b/other/GeneratedAI/DistributedPopulationTrackerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPopulationTrackerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPopulationTrackerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPostInvasionObjectAI.py b/other/GeneratedAI/DistributedPostInvasionObjectAI.py
new file mode 100644
index 0000000..a9f54cf
--- /dev/null
+++ b/other/GeneratedAI/DistributedPostInvasionObjectAI.py
@@ -0,0 +1,15 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPostInvasionObjectAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPostInvasionObjectAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
+
+    def d_setOnFire(self, isOnFire):
+    	if isOnFire == True:
+    		self.sendUpdate('setOnFire', [
+    			isOnFire])
+    	else:
+    		return None
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPotionCraftingTableAI.py b/other/GeneratedAI/DistributedPotionCraftingTableAI.py
new file mode 100644
index 0000000..ddeee1c
--- /dev/null
+++ b/other/GeneratedAI/DistributedPotionCraftingTableAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPotionCraftingTableAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPotionCraftingTableAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedPotionGameAI.py b/other/GeneratedAI/DistributedPotionGameAI.py
new file mode 100644
index 0000000..f4eb71d
--- /dev/null
+++ b/other/GeneratedAI/DistributedPotionGameAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedPotionGameAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedPotionGameAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedQuestAI.py b/other/GeneratedAI/DistributedQuestAI.py
new file mode 100644
index 0000000..060cb82
--- /dev/null
+++ b/other/GeneratedAI/DistributedQuestAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedQuestAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedQuestAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedQuestGiverAI.py b/other/GeneratedAI/DistributedQuestGiverAI.py
new file mode 100644
index 0000000..77f11e4
--- /dev/null
+++ b/other/GeneratedAI/DistributedQuestGiverAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedQuestGiverAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedQuestGiverAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedQuestPropAI.py b/other/GeneratedAI/DistributedQuestPropAI.py
new file mode 100644
index 0000000..7793bbc
--- /dev/null
+++ b/other/GeneratedAI/DistributedQuestPropAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedQuestPropAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedQuestPropAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedRavenAI.py b/other/GeneratedAI/DistributedRavenAI.py
new file mode 100644
index 0000000..2d48644
--- /dev/null
+++ b/other/GeneratedAI/DistributedRavenAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedRavenAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedRavenAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedRepairBenchAI.py b/other/GeneratedAI/DistributedRepairBenchAI.py
new file mode 100644
index 0000000..9898d64
--- /dev/null
+++ b/other/GeneratedAI/DistributedRepairBenchAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedRepairBenchAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedRepairBenchAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedRepairGameAI.py b/other/GeneratedAI/DistributedRepairGameAI.py
new file mode 100644
index 0000000..b1fd05c
--- /dev/null
+++ b/other/GeneratedAI/DistributedRepairGameAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedRepairGameAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedRepairGameAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedScrimmageWorldAI.py b/other/GeneratedAI/DistributedScrimmageWorldAI.py
new file mode 100644
index 0000000..1f93ccb
--- /dev/null
+++ b/other/GeneratedAI/DistributedScrimmageWorldAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedScrimmageWorldAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedScrimmageWorldAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedSearchableContainerAI.py b/other/GeneratedAI/DistributedSearchableContainerAI.py
new file mode 100644
index 0000000..7021cbc
--- /dev/null
+++ b/other/GeneratedAI/DistributedSearchableContainerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedSearchableContainerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedSearchableContainerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedShipBroadsideAI.py b/other/GeneratedAI/DistributedShipBroadsideAI.py
new file mode 100644
index 0000000..8351aad
--- /dev/null
+++ b/other/GeneratedAI/DistributedShipBroadsideAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedShipBroadsideAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedShipBroadsideAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedShipCannonAI.py b/other/GeneratedAI/DistributedShipCannonAI.py
new file mode 100644
index 0000000..bc68032
--- /dev/null
+++ b/other/GeneratedAI/DistributedShipCannonAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedShipCannonAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedShipCannonAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedShipCannonUD.py b/other/GeneratedAI/DistributedShipCannonUD.py
new file mode 100644
index 0000000..bbd8f39
--- /dev/null
+++ b/other/GeneratedAI/DistributedShipCannonUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedShipCannonUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedShipCannonUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedShipDeployerAI.py b/other/GeneratedAI/DistributedShipDeployerAI.py
new file mode 100644
index 0000000..19cbcb4
--- /dev/null
+++ b/other/GeneratedAI/DistributedShipDeployerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedShipDeployerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedShipDeployerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedShipLoaderAI.py b/other/GeneratedAI/DistributedShipLoaderAI.py
new file mode 100644
index 0000000..1a10506
--- /dev/null
+++ b/other/GeneratedAI/DistributedShipLoaderAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedShipLoaderAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedShipLoaderAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedShipLoaderUD.py b/other/GeneratedAI/DistributedShipLoaderUD.py
new file mode 100644
index 0000000..7b02e69
--- /dev/null
+++ b/other/GeneratedAI/DistributedShipLoaderUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedShipLoaderUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedShipLoaderUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedShipRepairSpotAI.py b/other/GeneratedAI/DistributedShipRepairSpotAI.py
new file mode 100644
index 0000000..8ad4541
--- /dev/null
+++ b/other/GeneratedAI/DistributedShipRepairSpotAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedShipRepairSpotAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedShipRepairSpotAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedShippartAI.py b/other/GeneratedAI/DistributedShippartAI.py
new file mode 100644
index 0000000..832f9e2
--- /dev/null
+++ b/other/GeneratedAI/DistributedShippartAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedShippartAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedShippartAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedShippartUD.py b/other/GeneratedAI/DistributedShippartUD.py
new file mode 100644
index 0000000..242156c
--- /dev/null
+++ b/other/GeneratedAI/DistributedShippartUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedShippartUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedShippartUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedShopKeeperAI.py b/other/GeneratedAI/DistributedShopKeeperAI.py
new file mode 100644
index 0000000..b233c2c
--- /dev/null
+++ b/other/GeneratedAI/DistributedShopKeeperAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedShopKeeperAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedShopKeeperAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedSimpleShipAI.py b/other/GeneratedAI/DistributedSimpleShipAI.py
new file mode 100644
index 0000000..67a9bda
--- /dev/null
+++ b/other/GeneratedAI/DistributedSimpleShipAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedSimpleShipAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedSimpleShipAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedSmoothNodeAI.py b/other/GeneratedAI/DistributedSmoothNodeAI.py
new file mode 100644
index 0000000..36d05a9
--- /dev/null
+++ b/other/GeneratedAI/DistributedSmoothNodeAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedSmoothNodeAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedSmoothNodeAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedSteeringWheelAI.py b/other/GeneratedAI/DistributedSteeringWheelAI.py
new file mode 100644
index 0000000..2c341b7
--- /dev/null
+++ b/other/GeneratedAI/DistributedSteeringWheelAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedSteeringWheelAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedSteeringWheelAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedSteeringWheelUD.py b/other/GeneratedAI/DistributedSteeringWheelUD.py
new file mode 100644
index 0000000..0e524cc
--- /dev/null
+++ b/other/GeneratedAI/DistributedSteeringWheelUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedSteeringWheelUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedSteeringWheelUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedSurfaceTreasureAI.py b/other/GeneratedAI/DistributedSurfaceTreasureAI.py
new file mode 100644
index 0000000..2e3ffc2
--- /dev/null
+++ b/other/GeneratedAI/DistributedSurfaceTreasureAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedSurfaceTreasureAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedSurfaceTreasureAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTargetableObjectAI.py b/other/GeneratedAI/DistributedTargetableObjectAI.py
new file mode 100644
index 0000000..8dffbea
--- /dev/null
+++ b/other/GeneratedAI/DistributedTargetableObjectAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTargetableObjectAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTargetableObjectAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTeleportHandlerAI.py b/other/GeneratedAI/DistributedTeleportHandlerAI.py
new file mode 100644
index 0000000..f76ff50
--- /dev/null
+++ b/other/GeneratedAI/DistributedTeleportHandlerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTeleportHandlerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTeleportHandlerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTeleportMgrAI.py b/other/GeneratedAI/DistributedTeleportMgrAI.py
new file mode 100644
index 0000000..c239038
--- /dev/null
+++ b/other/GeneratedAI/DistributedTeleportMgrAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTeleportMgrAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTeleportMgrAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTeleportZoneAI.py b/other/GeneratedAI/DistributedTeleportZoneAI.py
new file mode 100644
index 0000000..4639d20
--- /dev/null
+++ b/other/GeneratedAI/DistributedTeleportZoneAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTeleportZoneAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTeleportZoneAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTeleportZoneUD.py b/other/GeneratedAI/DistributedTeleportZoneUD.py
new file mode 100644
index 0000000..b87ed58
--- /dev/null
+++ b/other/GeneratedAI/DistributedTeleportZoneUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTeleportZoneUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTeleportZoneUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTestObjectAI.py b/other/GeneratedAI/DistributedTestObjectAI.py
new file mode 100644
index 0000000..eba240f
--- /dev/null
+++ b/other/GeneratedAI/DistributedTestObjectAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTestObjectAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTestObjectAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTimeOfDayManagerAI.py b/other/GeneratedAI/DistributedTimeOfDayManagerAI.py
new file mode 100644
index 0000000..bc7cfb6
--- /dev/null
+++ b/other/GeneratedAI/DistributedTimeOfDayManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTimeOfDayManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTimeOfDayManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTravelAgentUD.py b/other/GeneratedAI/DistributedTravelAgentUD.py
new file mode 100644
index 0000000..5e1f1a9
--- /dev/null
+++ b/other/GeneratedAI/DistributedTravelAgentUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTravelAgentUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTravelAgentUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTreasureMapAI.py b/other/GeneratedAI/DistributedTreasureMapAI.py
new file mode 100644
index 0000000..9e141f4
--- /dev/null
+++ b/other/GeneratedAI/DistributedTreasureMapAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTreasureMapAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTreasureMapAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTreasureMapInstanceAI.py b/other/GeneratedAI/DistributedTreasureMapInstanceAI.py
new file mode 100644
index 0000000..c682568
--- /dev/null
+++ b/other/GeneratedAI/DistributedTreasureMapInstanceAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTreasureMapInstanceAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTreasureMapInstanceAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTreasureMapUD.py b/other/GeneratedAI/DistributedTreasureMapUD.py
new file mode 100644
index 0000000..088f60a
--- /dev/null
+++ b/other/GeneratedAI/DistributedTreasureMapUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTreasureMapUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTreasureMapUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTutorialShipCannonAI.py b/other/GeneratedAI/DistributedTutorialShipCannonAI.py
new file mode 100644
index 0000000..e7843a3
--- /dev/null
+++ b/other/GeneratedAI/DistributedTutorialShipCannonAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTutorialShipCannonAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTutorialShipCannonAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedTutorialSimpleShipAI.py b/other/GeneratedAI/DistributedTutorialSimpleShipAI.py
new file mode 100644
index 0000000..00b5e08
--- /dev/null
+++ b/other/GeneratedAI/DistributedTutorialSimpleShipAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedTutorialSimpleShipAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedTutorialSimpleShipAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedVoodooZombieAI.py b/other/GeneratedAI/DistributedVoodooZombieAI.py
new file mode 100644
index 0000000..c67dd84
--- /dev/null
+++ b/other/GeneratedAI/DistributedVoodooZombieAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedVoodooZombieAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedVoodooZombieAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedWeaponAI.py b/other/GeneratedAI/DistributedWeaponAI.py
new file mode 100644
index 0000000..9d79f58
--- /dev/null
+++ b/other/GeneratedAI/DistributedWeaponAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedWeaponAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedWeaponAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedWeaponUD.py b/other/GeneratedAI/DistributedWeaponUD.py
new file mode 100644
index 0000000..c70b8b5
--- /dev/null
+++ b/other/GeneratedAI/DistributedWeaponUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedWeaponUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedWeaponUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedWelcomeWorldAI.py b/other/GeneratedAI/DistributedWelcomeWorldAI.py
new file mode 100644
index 0000000..cc9a88d
--- /dev/null
+++ b/other/GeneratedAI/DistributedWelcomeWorldAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedWelcomeWorldAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedWelcomeWorldAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedWreckAI.py b/other/GeneratedAI/DistributedWreckAI.py
new file mode 100644
index 0000000..a3512de
--- /dev/null
+++ b/other/GeneratedAI/DistributedWreckAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedWreckAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedWreckAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedWreckedDelFuegoTownAI.py b/other/GeneratedAI/DistributedWreckedDelFuegoTownAI.py
new file mode 100644
index 0000000..2dc34f6
--- /dev/null
+++ b/other/GeneratedAI/DistributedWreckedDelFuegoTownAI.py
@@ -0,0 +1,8 @@
+from pirates.invasion.DistributedPostInvasionObjectAI import DistributedPostInvasionObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedWreckedDelFuegoTownAI(DistributedPostInvasionObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedWreckedDelFuegoTownAI')
+
+    def __init__(self, air):
+        DistributedPostInvasionObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedWreckedFaithfulBrideAI.py b/other/GeneratedAI/DistributedWreckedFaithfulBrideAI.py
new file mode 100644
index 0000000..889aa6d
--- /dev/null
+++ b/other/GeneratedAI/DistributedWreckedFaithfulBrideAI.py
@@ -0,0 +1,8 @@
+from pirates.invasion.DistributedPostInvasionObjectAI import DistributedPostInvasionObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedWreckedFaithfulBrideAI(DistributedPostInvasionObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedWreckedFaithfulBrideAI')
+
+    def __init__(self, air):
+        DistributedPostInvasionObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/DistributedWreckedGovernorsMansionAI.py b/other/GeneratedAI/DistributedWreckedGovernorsMansionAI.py
new file mode 100644
index 0000000..700850f
--- /dev/null
+++ b/other/GeneratedAI/DistributedWreckedGovernorsMansionAI.py
@@ -0,0 +1,8 @@
+from pirates.invasion.DistributedPostInvasionObjectAI import DistributedPostInvasionObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class DistributedWreckedGovernorsMansionAI(DistributedPostInvasionObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('DistributedWreckedGovernorsMansionAI')
+
+    def __init__(self, air):
+        DistributedPostInvasionObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/FriendManagerAI.py b/other/GeneratedAI/FriendManagerAI.py
new file mode 100644
index 0000000..0b93a23
--- /dev/null
+++ b/other/GeneratedAI/FriendManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class FriendManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('FriendManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/GrabberTentacleAI.py b/other/GeneratedAI/GrabberTentacleAI.py
new file mode 100644
index 0000000..8c65db8
--- /dev/null
+++ b/other/GeneratedAI/GrabberTentacleAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class GrabberTentacleAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('GrabberTentacleAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/GuildManagerAI.py b/other/GeneratedAI/GuildManagerAI.py
new file mode 100644
index 0000000..139c440
--- /dev/null
+++ b/other/GeneratedAI/GuildManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class GuildManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('GuildManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/GuildManagerUD.py b/other/GeneratedAI/GuildManagerUD.py
new file mode 100644
index 0000000..bb82e93
--- /dev/null
+++ b/other/GeneratedAI/GuildManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class GuildManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('GuildManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/HolderTentacleAI.py b/other/GeneratedAI/HolderTentacleAI.py
new file mode 100644
index 0000000..67283b5
--- /dev/null
+++ b/other/GeneratedAI/HolderTentacleAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class HolderTentacleAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('HolderTentacleAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/HolidayManagerAI.py b/other/GeneratedAI/HolidayManagerAI.py
new file mode 100644
index 0000000..9f6bcea
--- /dev/null
+++ b/other/GeneratedAI/HolidayManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class HolidayManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('HolidayManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/HolidayManagerUD.py b/other/GeneratedAI/HolidayManagerUD.py
new file mode 100644
index 0000000..54ec5a3
--- /dev/null
+++ b/other/GeneratedAI/HolidayManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class HolidayManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('HolidayManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/KrakenAI.py b/other/GeneratedAI/KrakenAI.py
new file mode 100644
index 0000000..cf4d650
--- /dev/null
+++ b/other/GeneratedAI/KrakenAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class KrakenAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('KrakenAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/KrakenBodyAI.py b/other/GeneratedAI/KrakenBodyAI.py
new file mode 100644
index 0000000..1fe0ba2
--- /dev/null
+++ b/other/GeneratedAI/KrakenBodyAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class KrakenBodyAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('KrakenBodyAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/KrakenHeadAI.py b/other/GeneratedAI/KrakenHeadAI.py
new file mode 100644
index 0000000..f27996e
--- /dev/null
+++ b/other/GeneratedAI/KrakenHeadAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class KrakenHeadAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('KrakenHeadAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/LootableAI.py b/other/GeneratedAI/LootableAI.py
new file mode 100644
index 0000000..880acc1
--- /dev/null
+++ b/other/GeneratedAI/LootableAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class LootableAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('LootableAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/MagicWordManagerAI.py b/other/GeneratedAI/MagicWordManagerAI.py
new file mode 100644
index 0000000..49836df
--- /dev/null
+++ b/other/GeneratedAI/MagicWordManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class MagicWordManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('MagicWordManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/NewsManagerAI.py b/other/GeneratedAI/NewsManagerAI.py
new file mode 100644
index 0000000..83f1027
--- /dev/null
+++ b/other/GeneratedAI/NewsManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class NewsManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('NewsManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/ObjectServerAI.py b/other/GeneratedAI/ObjectServerAI.py
new file mode 100644
index 0000000..a166ca1
--- /dev/null
+++ b/other/GeneratedAI/ObjectServerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class ObjectServerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('ObjectServerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/ObjectServerUD.py b/other/GeneratedAI/ObjectServerUD.py
new file mode 100644
index 0000000..aca707f
--- /dev/null
+++ b/other/GeneratedAI/ObjectServerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class ObjectServerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('ObjectServerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/OtpAvatarManagerAI.py b/other/GeneratedAI/OtpAvatarManagerAI.py
new file mode 100644
index 0000000..410f521
--- /dev/null
+++ b/other/GeneratedAI/OtpAvatarManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class OtpAvatarManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('OtpAvatarManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/OtpAvatarManagerUD.py b/other/GeneratedAI/OtpAvatarManagerUD.py
new file mode 100644
index 0000000..688c0b8
--- /dev/null
+++ b/other/GeneratedAI/OtpAvatarManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class OtpAvatarManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('OtpAvatarManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PCAvatarFriendsManagerUD.py b/other/GeneratedAI/PCAvatarFriendsManagerUD.py
new file mode 100644
index 0000000..2cfe536
--- /dev/null
+++ b/other/GeneratedAI/PCAvatarFriendsManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class PCAvatarFriendsManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PCAvatarFriendsManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PCGuildManagerAI.py b/other/GeneratedAI/PCGuildManagerAI.py
new file mode 100644
index 0000000..84fca98
--- /dev/null
+++ b/other/GeneratedAI/PCGuildManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PCGuildManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PCGuildManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PCGuildManagerUD.py b/other/GeneratedAI/PCGuildManagerUD.py
new file mode 100644
index 0000000..d5b5e13
--- /dev/null
+++ b/other/GeneratedAI/PCGuildManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class PCGuildManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PCGuildManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PCPlayerFriendsManagerUD.py b/other/GeneratedAI/PCPlayerFriendsManagerUD.py
new file mode 100644
index 0000000..b93ebb2
--- /dev/null
+++ b/other/GeneratedAI/PCPlayerFriendsManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class PCPlayerFriendsManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PCPlayerFriendsManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PSnapshotRendererAI.py b/other/GeneratedAI/PSnapshotRendererAI.py
new file mode 100644
index 0000000..5377bf0
--- /dev/null
+++ b/other/GeneratedAI/PSnapshotRendererAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PSnapshotRendererAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PSnapshotRendererAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PSnapshotRendererUD.py b/other/GeneratedAI/PSnapshotRendererUD.py
new file mode 100644
index 0000000..b16b8f3
--- /dev/null
+++ b/other/GeneratedAI/PSnapshotRendererUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class PSnapshotRendererUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PSnapshotRendererUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PVPGameBaseAI.py b/other/GeneratedAI/PVPGameBaseAI.py
new file mode 100644
index 0000000..82db5f5
--- /dev/null
+++ b/other/GeneratedAI/PVPGameBaseAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PVPGameBaseAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PVPGameBaseAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PVPGameBattleAI.py b/other/GeneratedAI/PVPGameBattleAI.py
new file mode 100644
index 0000000..e074fa0
--- /dev/null
+++ b/other/GeneratedAI/PVPGameBattleAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PVPGameBattleAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PVPGameBattleAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PVPGameCTLAI.py b/other/GeneratedAI/PVPGameCTLAI.py
new file mode 100644
index 0000000..0d73cc2
--- /dev/null
+++ b/other/GeneratedAI/PVPGameCTLAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PVPGameCTLAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PVPGameCTLAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PVPGamePirateerAI.py b/other/GeneratedAI/PVPGamePirateerAI.py
new file mode 100644
index 0000000..12c687c
--- /dev/null
+++ b/other/GeneratedAI/PVPGamePirateerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PVPGamePirateerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PVPGamePirateerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PVPGameShipBattleAI.py b/other/GeneratedAI/PVPGameShipBattleAI.py
new file mode 100644
index 0000000..7327299
--- /dev/null
+++ b/other/GeneratedAI/PVPGameShipBattleAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PVPGameShipBattleAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PVPGameShipBattleAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PVPGameTeamBattleAI.py b/other/GeneratedAI/PVPGameTeamBattleAI.py
new file mode 100644
index 0000000..aba8248
--- /dev/null
+++ b/other/GeneratedAI/PVPGameTeamBattleAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PVPGameTeamBattleAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PVPGameTeamBattleAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PVPManagerAI.py b/other/GeneratedAI/PVPManagerAI.py
new file mode 100644
index 0000000..1f5132f
--- /dev/null
+++ b/other/GeneratedAI/PVPManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PVPManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PVPManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PirateInventoryAI.py b/other/GeneratedAI/PirateInventoryAI.py
new file mode 100644
index 0000000..4230ecd
--- /dev/null
+++ b/other/GeneratedAI/PirateInventoryAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PirateInventoryAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PirateInventoryAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PirateInventoryUD.py b/other/GeneratedAI/PirateInventoryUD.py
new file mode 100644
index 0000000..2ca66bb
--- /dev/null
+++ b/other/GeneratedAI/PirateInventoryUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class PirateInventoryUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PirateInventoryUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PiratesDistrictAI.py b/other/GeneratedAI/PiratesDistrictAI.py
new file mode 100644
index 0000000..3a80ebf
--- /dev/null
+++ b/other/GeneratedAI/PiratesDistrictAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PiratesDistrictAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PiratesDistrictAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PiratesMagicWordManagerAI.py b/other/GeneratedAI/PiratesMagicWordManagerAI.py
new file mode 100644
index 0000000..dbe36fb
--- /dev/null
+++ b/other/GeneratedAI/PiratesMagicWordManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PiratesMagicWordManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PiratesMagicWordManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PiratesSettingsMgrAI.py b/other/GeneratedAI/PiratesSettingsMgrAI.py
new file mode 100644
index 0000000..1614468
--- /dev/null
+++ b/other/GeneratedAI/PiratesSettingsMgrAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PiratesSettingsMgrAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PiratesSettingsMgrAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PiratesSettingsMgrUD.py b/other/GeneratedAI/PiratesSettingsMgrUD.py
new file mode 100644
index 0000000..3242228
--- /dev/null
+++ b/other/GeneratedAI/PiratesSettingsMgrUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class PiratesSettingsMgrUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PiratesSettingsMgrUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PiratesSpeedchatRelayUD.py b/other/GeneratedAI/PiratesSpeedchatRelayUD.py
new file mode 100644
index 0000000..25fbc34
--- /dev/null
+++ b/other/GeneratedAI/PiratesSpeedchatRelayUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class PiratesSpeedchatRelayUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PiratesSpeedchatRelayUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PiratesTimeManagerAI.py b/other/GeneratedAI/PiratesTimeManagerAI.py
new file mode 100644
index 0000000..118a8ac
--- /dev/null
+++ b/other/GeneratedAI/PiratesTimeManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PiratesTimeManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PiratesTimeManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PiratesTutorialManagerAI.py b/other/GeneratedAI/PiratesTutorialManagerAI.py
new file mode 100644
index 0000000..e4997d9
--- /dev/null
+++ b/other/GeneratedAI/PiratesTutorialManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class PiratesTutorialManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PiratesTutorialManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/PlayerFriendsManagerUD.py b/other/GeneratedAI/PlayerFriendsManagerUD.py
new file mode 100644
index 0000000..f87b105
--- /dev/null
+++ b/other/GeneratedAI/PlayerFriendsManagerUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class PlayerFriendsManagerUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('PlayerFriendsManagerUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/ScoreboardAI.py b/other/GeneratedAI/ScoreboardAI.py
new file mode 100644
index 0000000..342dfe9
--- /dev/null
+++ b/other/GeneratedAI/ScoreboardAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class ScoreboardAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('ScoreboardAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/SettingsMgrAI.py b/other/GeneratedAI/SettingsMgrAI.py
new file mode 100644
index 0000000..4c4ad7a
--- /dev/null
+++ b/other/GeneratedAI/SettingsMgrAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class SettingsMgrAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('SettingsMgrAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/SettingsMgrUD.py b/other/GeneratedAI/SettingsMgrUD.py
new file mode 100644
index 0000000..020db30
--- /dev/null
+++ b/other/GeneratedAI/SettingsMgrUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class SettingsMgrUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('SettingsMgrUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/SiegeAnnouncerAI.py b/other/GeneratedAI/SiegeAnnouncerAI.py
new file mode 100644
index 0000000..304f26f
--- /dev/null
+++ b/other/GeneratedAI/SiegeAnnouncerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class SiegeAnnouncerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('SiegeAnnouncerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/SiegeManagerAI.py b/other/GeneratedAI/SiegeManagerAI.py
new file mode 100644
index 0000000..630939c
--- /dev/null
+++ b/other/GeneratedAI/SiegeManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class SiegeManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('SiegeManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/SnapshotDispatcherAI.py b/other/GeneratedAI/SnapshotDispatcherAI.py
new file mode 100644
index 0000000..f6cb363
--- /dev/null
+++ b/other/GeneratedAI/SnapshotDispatcherAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class SnapshotDispatcherAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('SnapshotDispatcherAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/SnapshotDispatcherUD.py b/other/GeneratedAI/SnapshotDispatcherUD.py
new file mode 100644
index 0000000..ba42699
--- /dev/null
+++ b/other/GeneratedAI/SnapshotDispatcherUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class SnapshotDispatcherUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('SnapshotDispatcherUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/SnapshotRendererAI.py b/other/GeneratedAI/SnapshotRendererAI.py
new file mode 100644
index 0000000..3631b4a
--- /dev/null
+++ b/other/GeneratedAI/SnapshotRendererAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class SnapshotRendererAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('SnapshotRendererAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/SnapshotRendererUD.py b/other/GeneratedAI/SnapshotRendererUD.py
new file mode 100644
index 0000000..89e6685
--- /dev/null
+++ b/other/GeneratedAI/SnapshotRendererUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class SnapshotRendererUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('SnapshotRendererUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/SpeedchatRelayUD.py b/other/GeneratedAI/SpeedchatRelayUD.py
new file mode 100644
index 0000000..ce95f30
--- /dev/null
+++ b/other/GeneratedAI/SpeedchatRelayUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class SpeedchatRelayUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('SpeedchatRelayUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/StatusDatabaseUD.py b/other/GeneratedAI/StatusDatabaseUD.py
new file mode 100644
index 0000000..bea2f72
--- /dev/null
+++ b/other/GeneratedAI/StatusDatabaseUD.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectGlobalUD import DistributedObjectGlobalUD
+from direct.directnotify import DirectNotifyGlobal
+
+class StatusDatabaseUD(DistributedObjectGlobalUD):
+    notify = DirectNotifyGlobal.directNotify.newCategory('StatusDatabaseUD')
+
+    def __init__(self, air):
+        DistributedObjectGlobalUD.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/TargetManagerAI.py b/other/GeneratedAI/TargetManagerAI.py
new file mode 100644
index 0000000..47aaeec
--- /dev/null
+++ b/other/GeneratedAI/TargetManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class TargetManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('TargetManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/TestObjectAI.py b/other/GeneratedAI/TestObjectAI.py
new file mode 100644
index 0000000..892f38f
--- /dev/null
+++ b/other/GeneratedAI/TestObjectAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class TestObjectAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('TestObjectAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/TimeManagerAI.py b/other/GeneratedAI/TimeManagerAI.py
new file mode 100644
index 0000000..4c1b280
--- /dev/null
+++ b/other/GeneratedAI/TimeManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class TimeManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('TimeManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/TradeAI.py b/other/GeneratedAI/TradeAI.py
new file mode 100644
index 0000000..1c0a980
--- /dev/null
+++ b/other/GeneratedAI/TradeAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class TradeAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('TradeAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/TradeManagerAI.py b/other/GeneratedAI/TradeManagerAI.py
new file mode 100644
index 0000000..d2e5351
--- /dev/null
+++ b/other/GeneratedAI/TradeManagerAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class TradeManagerAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('TradeManagerAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/TreasureMapBlackPearlAI.py b/other/GeneratedAI/TreasureMapBlackPearlAI.py
new file mode 100644
index 0000000..1db76c0
--- /dev/null
+++ b/other/GeneratedAI/TreasureMapBlackPearlAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class TreasureMapBlackPearlAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('TreasureMapBlackPearlAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
diff --git a/other/GeneratedAI/WeaponBaseAI.py b/other/GeneratedAI/WeaponBaseAI.py
new file mode 100644
index 0000000..6c761fa
--- /dev/null
+++ b/other/GeneratedAI/WeaponBaseAI.py
@@ -0,0 +1,8 @@
+from direct.distributed.DistributedObjectAI import DistributedObjectAI
+from direct.directnotify import DirectNotifyGlobal
+
+class WeaponBaseAI(DistributedObjectAI):
+    notify = DirectNotifyGlobal.directNotify.newCategory('WeaponBaseAI')
+
+    def __init__(self, air):
+        DistributedObjectAI.__init__(self, air)
\ No newline at end of file
