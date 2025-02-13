Generated with discovered.json: 0x37c416beab6e9efd14324f891519608460c17be7

# Diff at Tue, 01 Oct 2024 11:14:13 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@bd754dc73c66120164006054f8d25c5fae9cd910 block: 76950926
- current block number: 76950926

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 76950926 (main branch discovery), not current.

```diff
    contract RollupProxy (0x04ea347cC6A258A7F65D67aFb60B1d487062A1d0) {
    +++ description: Manages rollup components, list of Stakers and Validators. Entry point for Validators creating new Rollup Nodes (state commits) and Challengers submitting fraud proofs.
      values.$pastUpgrades:
+        [["2024-03-08T13:20:18.000Z",["0xEe9E5546A11Cb5b4A86e92DA05f2ef75C26E4754","0x0aE4dD666748bF0F6dB5c149Eab1D8aD27820A6A"]]]
      values.$upgradeCount:
+        1
    }
```

```diff
    contract UpgradeExecutor (0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9) {
    +++ description: None
      values.$pastUpgrades:
+        [["2024-03-08T13:20:18.000Z",["0x660ea1675F7323dC3Ba0c8dDFB593225Eb01E3C1"]]]
    }
```

```diff
    contract ERC20RollupEventInbox (0x0fF7A97caAb356c5507e5355b6819CB8b93d5591) {
    +++ description: None
      values.$pastUpgrades:
+        [["2024-03-08T13:20:18.000Z",["0x18FD37A4FB9E1F06d9383958aFd236771F15A8cb"]]]
    }
```

```diff
    contract ChallengeManager (0x383eFE8D410285c5CbE1B4F296022640759aA834) {
    +++ description: None
      values.$pastUpgrades:
+        [["2024-03-08T13:20:18.000Z",["0x09824fe72BFF474d16D9c2774432E381BBD60662"]]]
    }
```

```diff
    contract Outbox (0xA597e0212971e65f53f288Ff1fFd26A6C8201f83) {
    +++ description: None
      values.$pastUpgrades:
+        [["2024-03-08T13:20:18.000Z",["0x302275067251F5FcdB9359Bda735fD8f7A4A54c0"]]]
    }
```

```diff
    contract Bridge (0xD4FE46D2533E7d03382ac6cACF0547F336e59DC0) {
    +++ description: None
      values.$pastUpgrades:
+        [["2024-03-08T13:20:18.000Z",["0x2a6DD4433ffa96dc1755814FC0d9cc83A5F68DeC"]]]
    }
```

```diff
    contract SequencerInbox (0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77) {
    +++ description: State batches / commitments get posted here.
      values.$pastUpgrades:
+        [["2024-03-08T13:20:18.000Z",["0x1c6ACCd9d66f3B993928E7439c9A2d67b94a445F"]]]
    }
```

```diff
    contract Inbox (0xFF55fB76F5671dD9eB6c62EffF8D693Bb161a3ad) {
    +++ description: None
      values.$pastUpgrades:
+        [["2024-03-08T13:20:18.000Z",["0x7EfcB76D0e2E776A298aAa603d433336e5F8b6ab"]]]
    }
```

Generated with discovered.json: 0xd92c2e5a0b439c794c142166af9ca5064d9e846b

# Diff at Wed, 25 Sep 2024 10:31:38 GMT:

- author: sekuba (<sekuba@users.noreply.github.com>)
- comparing to: main@e8c4fe6b10f7918ebbd761bc35018ba84053b08c block: 75299946
- current block number: 76950926

## Description

DAC keyset update from 1/1 to 1/2.

## Watched changes

```diff
    contract SequencerInbox (0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77) {
    +++ description: State batches / commitments get posted here.
      values.dacKeyset.membersCount:
-        1
+        2
      values.dacKeyset.blsSignatures.1:
+        "YAImQLIbSOCL4/9H1Cz7q4xAOZPVli5CulIEqvuMF4JjZwEhRDa8n3tie56cEykcxhgd8kixHEdOm2YcGOetbcUN7HUgfDpVMEqspHjIYzp06QM/IEC0SC2oUxsXorqewxPqukssVdSDsZQ26R/A9uZ2+wpHhGd8V9itDIRK+1HXzECMMd02yic2cyGjmOxPXAGfMay9PnLViYszEOKRNsiRWBO6Z6n8VP3GJF4S4/XFPHQ58wFxIi8zWR12BvzCbw6UUKohmrC2SIHtu9hJ6rbj3EcXlNGa/YsGatysgfcVR20/rMysbmqy7E1zhsYwvhRQaOBUpoVUzH4DajylpiJdWpbk46dlq0127k2vtGgWXNErbBRES1IK2cDfbP+Ztw=="
      values.dacKeyset.blsSignatures.0:
-        "YBWzTXaVO10A2bGxmXd05VrZ459e8tmeikH1duygtJ4YQRHbRMqSfKYL70moUWNp5xn0zhuvn3IIbTHU9QXSshb+NZQZIc7KuHFYFGJqXTkCp7pFXxIjIe4OLF4DGNedhAco+CG0t2Z3Izrb5E/Mx1nPp5Bj2CjHrJgH3KERfC//y7WtJkxjHRn3Vy8/6hyO7Qcn3uKftNi75ikkmZnldI1P9UQxaqVHqgW/Sp68ju6LI/omVsdK2Yn9+R1F2C2fbQySLyLeT2J3EU9cHFoxMpmBXg3+ACMi5JFLEEt6iMOj/eE3AKo+u+iIWOIrsARwzAfNEb2fJk+Dh01F89NfwBMpXx6UEhpyamXe54X22kXm/suWMKqj9ZLJtTXg21hkcA=="
+        "YBlgGETG0JAkF0lRA3szPn3L5opNuQWdu2c9OsvmyiFTuut4zl6E8tcgnXSzlX1cwxFb/dKGoetJtdHbrfN4a70U5wD5NXsMjvZGJC9grFkyEQ4gQfOfMcW/NX5CEp3FvBfLYp9lTR/sAjU/uZ7JNGMj1ol0xyYkOkyAQvbN7ri9z05Jo3H8hhHYpvAkaIpgVQw2nSQg1nlMMhmUdn0g2XEBzijYfDvQC3MZDurPXmiC9eARVq+gLXF57By/3m1u8hZoshxjU2aG24ukLjEXEqGvqDR158jZpQE7ZMtv8c7ma1XSUSXLqm1LQMWlK2FRJwErkKGyUQM4luTI4fGoycDnpdQq2eI6+TZXm2PYY1nJrPo7lMghYL+CLkCSCvMmPQ=="
      values.keySetUpdates:
-        1
+        4
    }
```

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 75299946 (main branch discovery), not current.

```diff
    contract RollupProxy (0x04ea347cC6A258A7F65D67aFb60B1d487062A1d0) {
    +++ description: Manages rollup components, list of Stakers and Validators. Entry point for Validators creating new Rollup Nodes (state commits) and Challengers submitting fraud proofs.
      usedTypes.0.arg.0x184884e1eb9fefdc158f6c8ac912bb183bf3cf83f0090317e0bc4ac5860baa39:
+        "ArbOS v32 wasmModuleRoot"
    }
```

Generated with discovered.json: 0xff8264538b3cc61536270a4379d5d98c0b79fb2d

# Diff at Sun, 01 Sep 2024 08:48:00 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@bee35b6cff7c52634ae8667cbb331e18ad4ec17a block: 75299946
- current block number: 75299946

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 75299946 (main branch discovery), not current.

```diff
    contract RollupProxy (0x04ea347cC6A258A7F65D67aFb60B1d487062A1d0) {
    +++ description: Manages rollup components, list of Stakers and Validators. Entry point for Validators creating new Rollup Nodes (state commits) and Challengers submitting fraud proofs.
+++ description: Root hash of the WASM module used for execution, like a fingerprint of the L2 logic. Can be associated with ArbOS versions.
      values.wasmModuleRoot:
-        "0xf4389b835497a910d7ba3ebfb77aa93da985634f3c052de1290360635be40c4a"
+        "ArbOS v11 wasmModuleRoot"
      usedTypes:
+        [{"typeCaster":"Mapping","arg":{"0xbb9d58e9527566138b682f3a207c0976d5359837f6e330f4017434cca983ff41":"ArbOS v1-rc1 wasmModuleRoot","0x9d68e40c47e3b87a8a7e6368cc52915720a6484bb2f47ceabad7e573e3a11232":"ArbOS v2.1 wasmModuleRoot","0x53c288a0ca7100c0f2db8ab19508763a51c7fd1be125d376d940a65378acaee7":"ArbOS v3 wasmModuleRoot","0x588762be2f364be15d323df2aa60ffff60f2b14103b34823b6f7319acd1ae7a3":"ArbOS v3.1 wasmModuleRoot","0xcfba6a883c50a1b4475ab909600fa88fc9cceed9e3ff6f43dccd2d27f6bd57cf":"ArbOS v3.2 wasmModuleRoot","0xa24ccdb052d92c5847e8ea3ce722442358db4b00985a9ee737c4e601b6ed9876":"ArbOS v4 wasmModuleRoot","0x1e09e6d9e35b93f33ed22b2bc8dc10bbcf63fdde5e8a1fb8cc1bcd1a52f14bd0":"ArbOS v5 wasmModuleRoot","0x3848eff5e0356faf1fc9cafecb789584c5e7f4f8f817694d842ada96613d8bab":"ArbOS v6 wasmModuleRoot","0x53dd4b9a3d807a8cbb4d58fbfc6a0857c3846d46956848cae0a1cc7eca2bb5a8":"ArbOS v7 wasmModuleRoot","0x2b20e1490d1b06299b222f3239b0ae07e750d8f3b4dedd19f500a815c1548bbc":"ArbOS v7.1 wasmModuleRoot","0xd1842bfbe047322b3f3b3635b5fe62eb611557784d17ac1d2b1ce9c170af6544":"ArbOS v9 wasmModuleRoot","0x6b94a7fc388fd8ef3def759297828dc311761e88d8179c7ee8d3887dc554f3c3":"ArbOS v10 wasmModuleRoot","0xda4e3ad5e7feacb817c21c8d0220da7650fe9051ece68a3f0b1c5d38bbb27b21":"ArbOS v10.1 wasmModuleRoot","0x0754e09320c381566cc0449904c377a52bd34a6b9404432e80afd573b67f7b17":"ArbOS v10.2 wasmModuleRoot","0xf559b6d4fa869472dabce70fe1c15221bdda837533dfd891916836975b434dec":"ArbOS v10.3 wasmModuleRoot","0xf4389b835497a910d7ba3ebfb77aa93da985634f3c052de1290360635be40c4a":"ArbOS v11 wasmModuleRoot","0x68e4fe5023f792d4ef584796c84d710303a5e12ea02d6e37e2b5e9c4332507c4":"ArbOS v11.1 wasmModuleRoot","0x8b104a2e80ac6165dc58b9048de12f301d70b02a0ab51396c22b4b4b802a16a4":"ArbOS v20 wasmModuleRoot","0xb0de9cb89e4d944ae6023a3b62276e54804c242fd8c4c2d8e6cc4450f5fa8b1b":"ArbOS v30 wasmModuleRoot","0x260f5fa5c3176a856893642e149cf128b5a8de9f828afec8d11184415dd8dc69":"ArbOS v31 wasmModuleRoot"}}]
    }
```

```diff
    contract UpgradeExecutor (0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9) {
    +++ description: None
      receivedPermissions.0.via:
-        []
    }
```

```diff
    contract ProxyAdmin (0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91) {
    +++ description: None
      receivedPermissions.6.via:
-        []
      receivedPermissions.5.via:
-        []
      receivedPermissions.4.via:
-        []
      receivedPermissions.3.via:
-        []
      receivedPermissions.2.via:
-        []
      receivedPermissions.1.via:
-        []
      receivedPermissions.0.via:
-        []
    }
```

Generated with discovered.json: 0xefcf9445b1f07719fc7066a741eb4924e815a54d

# Diff at Fri, 23 Aug 2024 09:58:50 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@67597c7d6c810bc726594446890178150240711e block: 75299946
- current block number: 75299946

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 75299946 (main branch discovery), not current.

```diff
    contract UpgradeExecutor (0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract ERC20RollupEventInbox (0x0fF7A97caAb356c5507e5355b6819CB8b93d5591) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract ChallengeManager (0x383eFE8D410285c5CbE1B4F296022640759aA834) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract Outbox (0xA597e0212971e65f53f288Ff1fFd26A6C8201f83) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract Bridge (0xD4FE46D2533E7d03382ac6cACF0547F336e59DC0) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

```diff
    contract SequencerInbox (0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77) {
    +++ description: State batches / commitments get posted here.
      values.$upgradeCount:
+        1
    }
```

```diff
    contract Inbox (0xFF55fB76F5671dD9eB6c62EffF8D693Bb161a3ad) {
    +++ description: None
      values.$upgradeCount:
+        1
    }
```

Generated with discovered.json: 0xa521d915b392a5579b9a10b0a2f57d5aeece9871

# Diff at Thu, 22 Aug 2024 12:15:40 GMT:

- author: vincfurc (<10850139+vincfurc@users.noreply.github.com>)
- comparing to: main@bf2d0ebf21a279d76dfafc24de12b751244afaf6 block: 74469390
- current block number: 75299946

## Description

New handler now fetching BLS signature keys of DAC members.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 74469390 (main branch discovery), not current.

```diff
    contract SequencerInbox (0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77) {
    +++ description: State batches / commitments get posted here.
      values.dacKeyset.blsSignatures:
+        ["YBWzTXaVO10A2bGxmXd05VrZ459e8tmeikH1duygtJ4YQRHbRMqSfKYL70moUWNp5xn0zhuvn3IIbTHU9QXSshb+NZQZIc7KuHFYFGJqXTkCp7pFXxIjIe4OLF4DGNedhAco+CG0t2Z3Izrb5E/Mx1nPp5Bj2CjHrJgH3KERfC//y7WtJkxjHRn3Vy8/6hyO7Qcn3uKftNi75ikkmZnldI1P9UQxaqVHqgW/Sp68ju6LI/omVsdK2Yn9+R1F2C2fbQySLyLeT2J3EU9cHFoxMpmBXg3+ACMi5JFLEEt6iMOj/eE3AKo+u+iIWOIrsARwzAfNEb2fJk+Dh01F89NfwBMpXx6UEhpyamXe54X22kXm/suWMKqj9ZLJtTXg21hkcA=="]
    }
```

Generated with discovered.json: 0x484e54e1326ffcb072ed7b99505b893e065a8625

# Diff at Wed, 21 Aug 2024 10:08:45 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@2f6dde3357bf5d79196b6e94f79d853a6c4ec72b block: 74469390
- current block number: 74469390

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 74469390 (main branch discovery), not current.

```diff
    contract RollupProxy (0x04ea347cC6A258A7F65D67aFb60B1d487062A1d0) {
    +++ description: Manages rollup components, list of Stakers and Validators. Entry point for Validators creating new Rollup Nodes (state commits) and Challengers submitting fraud proofs.
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9","via":[]}]
    }
```

```diff
    contract UpgradeExecutor (0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9) {
    +++ description: None
      assignedPermissions:
-        {"upgrade":["0x04ea347cC6A258A7F65D67aFb60B1d487062A1d0"]}
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91","via":[]}]
      receivedPermissions:
+        [{"permission":"upgrade","target":"0x04ea347cC6A258A7F65D67aFb60B1d487062A1d0","via":[]}]
    }
```

```diff
    contract ERC20RollupEventInbox (0x0fF7A97caAb356c5507e5355b6819CB8b93d5591) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91","via":[]}]
    }
```

```diff
    contract ProxyAdmin (0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91) {
    +++ description: None
      assignedPermissions:
-        {"upgrade":["0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9","0x0fF7A97caAb356c5507e5355b6819CB8b93d5591","0x383eFE8D410285c5CbE1B4F296022640759aA834","0xA597e0212971e65f53f288Ff1fFd26A6C8201f83","0xD4FE46D2533E7d03382ac6cACF0547F336e59DC0","0xFF55fB76F5671dD9eB6c62EffF8D693Bb161a3ad","0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77"]}
      receivedPermissions:
+        [{"permission":"upgrade","target":"0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9","via":[]},{"permission":"upgrade","target":"0x0fF7A97caAb356c5507e5355b6819CB8b93d5591","via":[]},{"permission":"upgrade","target":"0x383eFE8D410285c5CbE1B4F296022640759aA834","via":[]},{"permission":"upgrade","target":"0xA597e0212971e65f53f288Ff1fFd26A6C8201f83","via":[]},{"permission":"upgrade","target":"0xD4FE46D2533E7d03382ac6cACF0547F336e59DC0","via":[]},{"permission":"upgrade","target":"0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77","via":[]},{"permission":"upgrade","target":"0xFF55fB76F5671dD9eB6c62EffF8D693Bb161a3ad","via":[]}]
    }
```

```diff
    contract ChallengeManager (0x383eFE8D410285c5CbE1B4F296022640759aA834) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91","via":[]}]
    }
```

```diff
    contract Outbox (0xA597e0212971e65f53f288Ff1fFd26A6C8201f83) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91","via":[]}]
    }
```

```diff
    contract Bridge (0xD4FE46D2533E7d03382ac6cACF0547F336e59DC0) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91","via":[]}]
    }
```

```diff
    contract SequencerInbox (0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77) {
    +++ description: State batches / commitments get posted here.
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91","via":[]}]
    }
```

```diff
    contract Inbox (0xFF55fB76F5671dD9eB6c62EffF8D693Bb161a3ad) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91","via":[]}]
    }
```

Generated with discovered.json: 0x981c68dc7f14a65e059024f5d4dc28acba34656a

# Diff at Fri, 09 Aug 2024 12:04:53 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@bf40aa32f030fd312056ca0ef198c8550467d1d7 block: 74469390
- current block number: 74469390

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 74469390 (main branch discovery), not current.

```diff
    contract ProxyAdmin (0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91) {
    +++ description: None
      assignedPermissions.upgrade.6:
-        "0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9"
+        "0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77"
      assignedPermissions.upgrade.5:
-        "0x383eFE8D410285c5CbE1B4F296022640759aA834"
+        "0xFF55fB76F5671dD9eB6c62EffF8D693Bb161a3ad"
      assignedPermissions.upgrade.4:
-        "0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77"
+        "0xD4FE46D2533E7d03382ac6cACF0547F336e59DC0"
      assignedPermissions.upgrade.3:
-        "0x0fF7A97caAb356c5507e5355b6819CB8b93d5591"
+        "0xA597e0212971e65f53f288Ff1fFd26A6C8201f83"
      assignedPermissions.upgrade.2:
-        "0xFF55fB76F5671dD9eB6c62EffF8D693Bb161a3ad"
+        "0x383eFE8D410285c5CbE1B4F296022640759aA834"
      assignedPermissions.upgrade.1:
-        "0xA597e0212971e65f53f288Ff1fFd26A6C8201f83"
+        "0x0fF7A97caAb356c5507e5355b6819CB8b93d5591"
      assignedPermissions.upgrade.0:
-        "0xD4FE46D2533E7d03382ac6cACF0547F336e59DC0"
+        "0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9"
    }
```

Generated with discovered.json: 0xdc9c4c2c96a94f4a6f2125e019aaef2d394a928d

# Diff at Fri, 09 Aug 2024 10:14:52 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@1f0da1d0aab7bc6b3b5e54e7e93480bd98e57035 block: 74469390
- current block number: 74469390

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 74469390 (main branch discovery), not current.

```diff
    contract UpgradeExecutor (0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9) {
    +++ description: None
      assignedPermissions.admin:
-        ["0x04ea347cC6A258A7F65D67aFb60B1d487062A1d0"]
      assignedPermissions.upgrade:
+        ["0x04ea347cC6A258A7F65D67aFb60B1d487062A1d0"]
    }
```

```diff
    contract ProxyAdmin (0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91) {
    +++ description: None
      assignedPermissions.admin:
-        ["0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9","0x0fF7A97caAb356c5507e5355b6819CB8b93d5591","0x383eFE8D410285c5CbE1B4F296022640759aA834","0xA597e0212971e65f53f288Ff1fFd26A6C8201f83","0xD4FE46D2533E7d03382ac6cACF0547F336e59DC0","0xFF55fB76F5671dD9eB6c62EffF8D693Bb161a3ad","0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77"]
      assignedPermissions.upgrade:
+        ["0xD4FE46D2533E7d03382ac6cACF0547F336e59DC0","0xA597e0212971e65f53f288Ff1fFd26A6C8201f83","0xFF55fB76F5671dD9eB6c62EffF8D693Bb161a3ad","0x0fF7A97caAb356c5507e5355b6819CB8b93d5591","0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77","0x383eFE8D410285c5CbE1B4F296022640759aA834","0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9"]
    }
```

Generated with discovered.json: 0x821f94cff7e5ef847e878545c232714e518f85ed

# Diff at Tue, 30 Jul 2024 11:18:25 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@b2b6471ff62871f4956541f42ec025c356c08f7e block: 74469390
- current block number: 74469390

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 74469390 (main branch discovery), not current.

```diff
    contract RollupProxy (0x04ea347cC6A258A7F65D67aFb60B1d487062A1d0) {
    +++ description: Manages rollup components, list of Stakers and Validators. Entry point for Validators creating new Rollup Nodes (state commits) and Challengers submitting fraud proofs.
      fieldMeta:
+        {"confirmPeriodBlocks":{"description":"Challenge period. (Number of blocks until a node is confirmed)."},"wasmModuleRoot":{"description":"Root hash of the WASM module used for execution, like a fingerprint of the L2 logic. Can be associated with ArbOS versions."}}
    }
```

```diff
    contract SequencerInbox (0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77) {
    +++ description: State batches / commitments get posted here.
      fieldMeta:
+        {"maxTimeVariation":{"description":"Struct: delayBlocks, futureBlocks, delaySeconds, futureSeconds. onlyRollupOwner settable. Transactions can only be force-included after `delayBlocks` window (Sequencer-only) has passed."}}
    }
```

Generated with discovered.json: 0xb202839bf951a0726b981784616a7c5858e89925

# Diff at Mon, 22 Jul 2024 12:29:10 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- current block number: 74469390

## Description

Initial discovery: First L3 Optimium with an Optimium as host chain (nova). Admin EOA, unverified contracts, native token not on coingecko (TVL will be zero). Otherwise standard Orbit stack with custom native token.

## Initial discovery

```diff
+   Status: CREATED
    contract RollupProxy (0x04ea347cC6A258A7F65D67aFb60B1d487062A1d0)
    +++ description: Manages rollup components, list of Stakers and Validators. Entry point for Validators creating new Rollup Nodes (state commits) and Challengers submitting fraud proofs.
```

```diff
+   Status: CREATED
    contract UpgradeExecutor (0x0611b78A42903a537BE7a2f9a8783BE39AC63cD9)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ERC20RollupEventInbox (0x0fF7A97caAb356c5507e5355b6819CB8b93d5591)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OneStepProver0 (0x1135265fE014D3FA32B3507E325642B92aFFeAEb)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x27C7Bfd2cC11429e9b80c443b42FDBe4754F6c91)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ValidatorWalletCreator (0x2b0E04Dc90e3fA58165CB41E2834B44A56E766aF)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ChallengeManager (0x383eFE8D410285c5CbE1B4F296022640759aA834)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OneStepProverMath (0x4811500e0d376Fa8d2EA3CCb7c61E0afB4F5A7f1)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ValidatorUtils (0x6c21303F5986180B1394d2C89f3e883890E2867b)
    +++ description: None
```

```diff
+   Status: CREATED
    contract  (0x82709E8564ce17707a7C8420c9e48e9a8A88bfc1)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OneStepProverHostIo (0x89AF7C4C2198c426cFe6E86de0680A0850503e06)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OneStepProofEntry (0x99a2A31300816C1FA3f40818AC9280fe7271F878)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Outbox (0xA597e0212971e65f53f288Ff1fFd26A6C8201f83)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Bridge (0xD4FE46D2533E7d03382ac6cACF0547F336e59DC0)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OneStepProverMemory (0xDf94F0474F205D086dbc2e66D69a856FCf520622)
    +++ description: None
```

```diff
+   Status: CREATED
    contract SequencerInbox (0xe347C1223381b9Dcd6c0F61cf81c90175A7Bae77)
    +++ description: State batches / commitments get posted here.
```

```diff
+   Status: CREATED
    contract Inbox (0xFF55fB76F5671dD9eB6c62EffF8D693Bb161a3ad)
    +++ description: None
```
