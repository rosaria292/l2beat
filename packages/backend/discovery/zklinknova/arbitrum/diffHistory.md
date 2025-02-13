Generated with discovered.json: 0x696474d84edc29918adaffbf4da48bc353d65227

# Diff at Tue, 01 Oct 2024 11:13:10 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@bd754dc73c66120164006054f8d25c5fae9cd910 block: 249925893
- current block number: 249925893

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 249925893 (main branch discovery), not current.

```diff
    contract ArbitrumL2Gateway (0x7bd79DEd935B542fb22c74305a4d2A293C18483a) {
    +++ description: None
      values.$pastUpgrades:
+        [["2024-03-01T08:07:57.000Z",["0xA194FB4EaB262EC9886A119609bbB2800bdD3a2E"]],["2024-03-09T10:55:57.000Z",["0x413552461b0b2c13f117d885b52AaA2f23374B1D"]]]
    }
```

```diff
    contract L1ERC20Bridge (0xfB0Ad0B3C2605A7CA33d6badd0C685E11b8F5585) {
    +++ description: None
      values.$pastUpgrades:
+        [["2024-03-01T12:42:53.000Z",["0x5f58BcCE409CDaFBbD705e720743b1EfF9fef28c"]],["2024-04-04T06:25:57.000Z",["0x1202e0557A23531D09015C802e993d6423685FfB"]]]
    }
```

```diff
    contract zkLink (0xFF73a1a1d27951A005eb23276dc99CB7F8d5420A) {
    +++ description: None
      values.$pastUpgrades:
+        [["2024-03-01T08:07:08.000Z",["0x50efC7f1290479cb879473512D89fDC80B726211"]],["2024-03-09T10:39:17.000Z",["0x04C6a52f3bf9F73618cD70F234AdB95a73325D1e"]],["2024-04-22T02:29:43.000Z",["0xe2cd603BFAe63EEFBDf0C51485f835D8B419A305"]]]
    }
```

Generated with discovered.json: 0x4bae17fea069f73f6181cb0fe40028bcfe782345

# Diff at Wed, 04 Sep 2024 07:32:20 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@878a951312cec062f5003f6749f781861b0cdba1 block: 236183206
- current block number: 249925893

## Description

Change one signer of the MS.

## Watched changes

```diff
    contract ArbitrumOwner (0xa29fFe244898CBec19DFEaAfB5cE671389FfF60F) {
    +++ description: None
      values.$members.5:
-        "0x824C9364A6CF8f5EB542ad2ca8F5705561C8b1db"
+        "0xC75EFCffEE930706daec5CaCA012551f6a1845D7"
      values.$members.4:
-        "0xC75EFCffEE930706daec5CaCA012551f6a1845D7"
+        "0x24a257B7D975E7ec6219C4cFCbcF6E504253c7A9"
      values.$members.3:
-        "0x24a257B7D975E7ec6219C4cFCbcF6E504253c7A9"
+        "0xF801886AE2e127A269B0F11892edb54F692d02dF"
      values.$members.2:
-        "0xF801886AE2e127A269B0F11892edb54F692d02dF"
+        "0x4D9b22B92Ff9faFAc013f82faCA88BDa8E778cb5"
      values.$members.1:
-        "0x4D9b22B92Ff9faFAc013f82faCA88BDa8E778cb5"
+        "0x7785bccF9110C188Dad39bE49D4Cdf6c6CC03F10"
      values.$members.0:
-        "0x7785bccF9110C188Dad39bE49D4Cdf6c6CC03F10"
+        "0xd30898ECdc21C72250a5fd1dbD37FF7D63237Db5"
    }
```

Generated with discovered.json: 0x0245cb3dd9cb99d92c2dae199ed7505a82ab2878

# Diff at Fri, 30 Aug 2024 08:06:28 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@6c1bd1f41fadf5f2cb1c1805b5a2c6138a3ed35a block: 236183206
- current block number: 236183206

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 236183206 (main branch discovery), not current.

```diff
    contract ArbitrumProxyAdmin (0x48698A17D193bFc882395AC06a1DEdbb222F2917) {
    +++ description: None
      receivedPermissions.0.via:
-        []
    }
```

```diff
    contract ArbitrumOwner (0xa29fFe244898CBec19DFEaAfB5cE671389FfF60F) {
    +++ description: None
      receivedPermissions.1.via:
-        []
      receivedPermissions.0.via:
-        []
    }
```

Generated with discovered.json: 0x4fb288a3d6eccd2f8d0f1933ef73cb56b5a01660

# Diff at Fri, 23 Aug 2024 09:57:28 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@67597c7d6c810bc726594446890178150240711e block: 236183206
- current block number: 236183206

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 236183206 (main branch discovery), not current.

```diff
    contract ArbitrumL2Gateway (0x7bd79DEd935B542fb22c74305a4d2A293C18483a) {
    +++ description: None
      values.$upgradeCount:
+        2
    }
```

```diff
    contract L1ERC20Bridge (0xfB0Ad0B3C2605A7CA33d6badd0C685E11b8F5585) {
    +++ description: None
      values.$upgradeCount:
+        2
    }
```

```diff
    contract zkLink (0xFF73a1a1d27951A005eb23276dc99CB7F8d5420A) {
    +++ description: None
      values.$upgradeCount:
+        3
    }
```

Generated with discovered.json: 0xf5ed5654a4bf603d5d83fd21c51942d132645e0c

# Diff at Wed, 21 Aug 2024 10:07:50 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@2f6dde3357bf5d79196b6e94f79d853a6c4ec72b block: 236183206
- current block number: 236183206

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 236183206 (main branch discovery), not current.

```diff
    contract ArbitrumProxyAdmin (0x48698A17D193bFc882395AC06a1DEdbb222F2917) {
    +++ description: None
      assignedPermissions:
-        {"upgrade":["0xfB0Ad0B3C2605A7CA33d6badd0C685E11b8F5585"]}
      receivedPermissions:
+        [{"permission":"upgrade","target":"0xfB0Ad0B3C2605A7CA33d6badd0C685E11b8F5585","via":[]}]
    }
```

```diff
    contract ArbitrumL2Gateway (0x7bd79DEd935B542fb22c74305a4d2A293C18483a) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xa29fFe244898CBec19DFEaAfB5cE671389FfF60F","via":[]}]
    }
```

```diff
    contract ArbitrumOwner (0xa29fFe244898CBec19DFEaAfB5cE671389FfF60F) {
    +++ description: None
      assignedPermissions:
-        {"upgrade":["0x7bd79DEd935B542fb22c74305a4d2A293C18483a","0xFF73a1a1d27951A005eb23276dc99CB7F8d5420A"]}
      receivedPermissions:
+        [{"permission":"upgrade","target":"0x7bd79DEd935B542fb22c74305a4d2A293C18483a","via":[]},{"permission":"upgrade","target":"0xFF73a1a1d27951A005eb23276dc99CB7F8d5420A","via":[]}]
    }
```

```diff
    contract L1ERC20Bridge (0xfB0Ad0B3C2605A7CA33d6badd0C685E11b8F5585) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x48698A17D193bFc882395AC06a1DEdbb222F2917","via":[]}]
    }
```

```diff
    contract zkLink (0xFF73a1a1d27951A005eb23276dc99CB7F8d5420A) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xa29fFe244898CBec19DFEaAfB5cE671389FfF60F","via":[]}]
    }
```

Generated with discovered.json: 0xd0c699fa1ecd3ab39127652bf279e28e11fb35e4

# Diff at Fri, 09 Aug 2024 12:03:57 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@bf40aa32f030fd312056ca0ef198c8550467d1d7 block: 236183206
- current block number: 236183206

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 236183206 (main branch discovery), not current.

```diff
    contract ArbitrumOwner (0xa29fFe244898CBec19DFEaAfB5cE671389FfF60F) {
    +++ description: None
      assignedPermissions.upgrade.1:
-        "0x7bd79DEd935B542fb22c74305a4d2A293C18483a"
+        "0xFF73a1a1d27951A005eb23276dc99CB7F8d5420A"
      assignedPermissions.upgrade.0:
-        "0xFF73a1a1d27951A005eb23276dc99CB7F8d5420A"
+        "0x7bd79DEd935B542fb22c74305a4d2A293C18483a"
    }
```

Generated with discovered.json: 0x95ee912601a055d0374480a11c0f88d66cf984e0

# Diff at Fri, 09 Aug 2024 10:13:57 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@1f0da1d0aab7bc6b3b5e54e7e93480bd98e57035 block: 236183206
- current block number: 236183206

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 236183206 (main branch discovery), not current.

```diff
    contract ArbitrumProxyAdmin (0x48698A17D193bFc882395AC06a1DEdbb222F2917) {
    +++ description: None
      assignedPermissions.admin:
-        ["0xfB0Ad0B3C2605A7CA33d6badd0C685E11b8F5585"]
      assignedPermissions.upgrade:
+        ["0xfB0Ad0B3C2605A7CA33d6badd0C685E11b8F5585"]
    }
```

```diff
    contract ArbitrumOwner (0xa29fFe244898CBec19DFEaAfB5cE671389FfF60F) {
    +++ description: None
      assignedPermissions.admin:
-        ["0x7bd79DEd935B542fb22c74305a4d2A293C18483a","0xFF73a1a1d27951A005eb23276dc99CB7F8d5420A"]
      assignedPermissions.upgrade:
+        ["0xFF73a1a1d27951A005eb23276dc99CB7F8d5420A","0x7bd79DEd935B542fb22c74305a4d2A293C18483a"]
      values.$multisigThreshold:
-        "5 of 8 (63%)"
      values.getOwners:
-        ["0x7785bccF9110C188Dad39bE49D4Cdf6c6CC03F10","0x4D9b22B92Ff9faFAc013f82faCA88BDa8E778cb5","0xF801886AE2e127A269B0F11892edb54F692d02dF","0x24a257B7D975E7ec6219C4cFCbcF6E504253c7A9","0xC75EFCffEE930706daec5CaCA012551f6a1845D7","0x824C9364A6CF8f5EB542ad2ca8F5705561C8b1db","0xd8F26118505417Ef6468Ac8A2AE1E5117245Db92","0xcC1A2bd1a459be0C7fAd3B7F9Fa9a6CBBFE9BFa5"]
      values.getThreshold:
-        5
      values.$members:
+        ["0x7785bccF9110C188Dad39bE49D4Cdf6c6CC03F10","0x4D9b22B92Ff9faFAc013f82faCA88BDa8E778cb5","0xF801886AE2e127A269B0F11892edb54F692d02dF","0x24a257B7D975E7ec6219C4cFCbcF6E504253c7A9","0xC75EFCffEE930706daec5CaCA012551f6a1845D7","0x824C9364A6CF8f5EB542ad2ca8F5705561C8b1db","0xd8F26118505417Ef6468Ac8A2AE1E5117245Db92","0xcC1A2bd1a459be0C7fAd3B7F9Fa9a6CBBFE9BFa5"]
      values.$threshold:
+        5
      values.multisigThreshold:
+        "5 of 8 (63%)"
    }
```

Generated with discovered.json: 0x597584cf793814ce5a34508814da3c40519a17dd

# Diff at Fri, 26 Jul 2024 08:09:58 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@f98f9bf0ba32e20ec33942af664ae6ed27e8172d block: 231384315
- current block number: 236183206

## Description

The admin / owner MS threshold is lowered to 5/8.

## Watched changes

```diff
    contract ArbitrumOwner (0xa29fFe244898CBec19DFEaAfB5cE671389FfF60F) {
    +++ description: None
      values.$multisigThreshold:
-        "6 of 8 (75%)"
+        "5 of 8 (63%)"
      values.getThreshold:
-        6
+        5
    }
```

Generated with discovered.json: 0x85cbc6a4cd4dcbb2283e6b810b1867b8faaeacc6

# Diff at Thu, 04 Jul 2024 14:08:47 GMT:

- author: Luca Donno (<donnoh99@gmail.com>)
- current block number: 228694559

## Description

Provide description of changes. This section will be preserved.

## Initial discovery

```diff
+   Status: CREATED
    contract ArbitrumProxyAdmin (0x48698A17D193bFc882395AC06a1DEdbb222F2917)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ArbitrumL2Gateway (0x7bd79DEd935B542fb22c74305a4d2A293C18483a)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ArbitrumOwner (0xa29fFe244898CBec19DFEaAfB5cE671389FfF60F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1ERC20Bridge (0xfB0Ad0B3C2605A7CA33d6badd0C685E11b8F5585)
    +++ description: None
```

```diff
+   Status: CREATED
    contract zkLink (0xFF73a1a1d27951A005eb23276dc99CB7F8d5420A)
    +++ description: None
```
