const allowedPlayers = ["HASSANxSIGMA_","ShortStack_YT", "X_LITTLE_MONSTER_X"];
      customAttributes: {enchantments: {"Attack Speed": 2,"Quick Charge": 3}, enchantmentTier: "Tier 5"},
      customDisplayName: "Enchanted Bow",
      customDescription: ""
    });
    
    api.giveItem(playerId, "Diamond Mace", 1, {
      customAttributes: {enchantments: {"Damage": 3,"Attack Speed": 2}, enchantmentTier: "Tier 5"},
      customDisplayName: "Enchanted Mace",
      customDescription: ""
    });
    
    api.giveItem(playerId, "Diamond Spear", 1, {
      customAttributes: {enchantments: {"Damage": 3,"Attack Speed": 2}, enchantmentTier: "Tier 5"},
      customDisplayName: "Enchanted Spear",
      customDescription: ""
    });
    
    // ✅ YOUR ENCHANTED ARMOR
    api.setItemSlot(playerId, 46, "Diamond Helmet", 1, {
      customAttributes: {
        enchantments: { Protection: 3, "Health Regen": 2 },
        enchantmentTier: "Tier 5"
      }
    });
    api.setItemSlot(playerId, 47, "Diamond Chestplate", 1, {
      customAttributes: {
        enchantments: { Protection: 3, "Health Regen": 2 },
        enchantmentTier: "Tier 5"
      }
    });
    api.setItemSlot(playerId, 48, "Diamond Gauntlets", 1, {
      customAttributes: {
        enchantments: { Protection: 3, "Health Regen": 2 },
        enchantmentTier: "Tier 5"
      }
    });
    api.setItemSlot(playerId, 49, "Diamond Leggings", 1, {
      customAttributes: {
        enchantments: { Protection: 3, "Health Regen": 2 },
        enchantmentTier: "Tier 5"
      }
    });
    api.setItemSlot(playerId, 50, "Diamond Boots", 1, {
      customAttributes: {
        enchantments: { Protection: 3, "Health Regen": 2 },
        enchantmentTier: "Tier 5"
      }
    });
    
    // ✅ ALL YOUR OTHER ITEMS
    api.giveItem(playerId, "Diamond Hang Glider", 1);
    api.giveItem(playerId, "Iceball", 999);
    api.giveItem(playerId, "Baked Potato", 999);
    api.giveItem(playerId, "Net", 999);
    api.giveItem(playerId, "Diamond Spikes", 999);
    api.giveItem(playerId, "Mango", 999);
    api.giveItem(playerId, "Compressed Messy Stone", 999);
    api.giveItem(playerId, "Arrow of Poison", 999);
    api.giveItem(playerId, "Rainbow Firecracker", 999);
    api.giveItem(playerId, "Pear", 100);
    
    api.sendMessage(playerId, "✅ FULL ENCHANTED RESTOCK COMPLETE!", { color: "gold" });
    return false;
  }
  
  return false;
};
