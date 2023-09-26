public static boolean checkEntity(BlockPos pos) {
        for (Entity entity : BlockUtil.mc.world.getEntitiesWithinAABB(Entity.class, new AxisAlignedBB(pos))) {
            if (entity.isDead || entity instanceof EntityItem || entity instanceof EntityXPOrb || entity instanceof EntityExpBottle || entity instanceof EntityArrow || entity instanceof EntityArmorStand) continue;
            return true;
        }
        return false;
    }
