scripts
=======

function attackHook(attacker, victim) { if(getCarriedItem()==331) { var mh= Entity.getHealth(v); Entity.setHealth(v,mh-9); } else if(getCarriedItem()==351,4) { ex=Entity.getX(v); ey=Entity.getY(v); ez=Entity.getZ(v); explode(ex,ey,ez,0.8); } }
