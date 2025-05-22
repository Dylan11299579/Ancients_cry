# Ancients_cry
The cry of the final machines 
type: boss
name: origin
description: the king of the plague. will go over all terrain .
hovering: true
hoverable: true
shadowElevation: 0.1
mechFrontSway: 0
mechSideSway: 0
mechStride: 0
drag: 0.06
outlineColor: 44413c
speed: 0.7
rotateSpeed: 2
accel: 0.095
groundLayer: 60
health: 2000000
armor: 490
hitSize: 20
canDrown: false
researchCostMultiplier: 1.5
research: {
  parent: 10j-03-hover-mounting-bay
  objectives: [
    10j-03-hover-mounting-bay
  ]
}
abilities: [
  {
    type: MoveEffectAbility
    teamColor: true
    effect: missileTrailShort
    x: 0
    y: -6.6
    interval: 4
    minVelocity: 0.6
  }
]
engines: [
  {
    x: 0
    y: -6.6
    radius: 1.5
  }
]
itemCapacity: 0
useEngineElevation: false
lowAltitude: true
weapons: [
  {
    x: 1.7
    y: 1
    mirror: true
    alternate: true
    reload: 48
    rotate: true
    shootSound: missile
    shoot: {
      shots: 3
      shotDelay: 5
    }
    bullet: {
      type: brokenbolttype
      speed: 10
      lifetime: 70
      damage: 2000
      width: 2
      height: 10
      trailWidth: 3
      trailLength: 8
      pierce: false
      shrinkX: 0
      shrinkY: 0
    }
  }
}
