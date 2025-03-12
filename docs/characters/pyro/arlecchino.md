---
description: '"The Knave," Fourth of the Fatui Harbingers. A poised, ruthless diplomat. To the children in the House of the Hearth, she is their feared yet dependable "Father."'
---

import char from '@site/src/data/characters/Arlecchino.json'
import SkillIcon from '@site/src/components/char/SkillIcon'

# Arlecchino

<!-- Remove this warning when adding the basic mechs ticket -->
import NoBasicMechs from '@site/src/components/char/NoBasicMechs'

<NoBasicMechs />

import Image from '@theme/IdealImage'

<Image img={require('/img/characters/gacha/Arlecchino.png')} alt="Arlecchino's gacha art" />
<blockquote>{frontMatter.description}</blockquote>

## Resources

* [Arlecchino Quick Guide](https://keqingmains.com/q/arlecchino-quickguide/)

## Base Stats

import CharStatsTable from '@site/src/components/char/CharStatsTable'

<CharStatsTable char={char} />

## Attacks

import Skill from '@site/src/components/char/Skill'

<Tabs queryString="ability">
<TabItem value='na' label='Normal Attacks'>
<SkillIcon char={char} skill='na' />
<div class='talent-columns'>
<Skill char={char} skill='na' sectionFilter='Normal Attack' />

</div>
<div class='talent-columns'>
<Skill char={char} skill='na' sectionFilter='Charged Attack' />


</div>
<div class='talent-columns'>
<Skill char={char} skill='na' sectionFilter='Plunging Attack' />


</div>

<!--
**Notes**

* MV/s are calculated using the shortest possible frames without any animation cancels, for different cancels see [below](#frames).

-->

</TabItem>

<TabItem value='e' label='Skill'>
<SkillIcon char={char} skill='e' />
<div class='talent-columns'>
<Skill char={char} skill='e' />


</div>

**Notes**


</TabItem>

<TabItem value='q' label='Burst'>
<SkillIcon char={char} skill='q' />
<div class='talent-columns'>
<Skill char={char} skill='q'/>

</div>

**Notes**


</TabItem>
</Tabs>

<!--
## Frames

import charFrames from '@site/src/data/frames/Arlecchino.json'
import Frames from '@site/src/components/char/Frames'

<Frames data={charFrames} />
-->

## Ascension Passives

import Passive from '@site/src/components/char/Passive'

<Tabs queryString="passive">
<TabItem value='passive' label='Passive'>
<Passive char={char} passive={2} />
</TabItem>

<TabItem value='a1' label='Ascension 1'>
<Passive char={char} passive={0} />
</TabItem>

<TabItem value="a4" label="Ascension 4">
<Passive char={char} passive={1} />
</TabItem>
</Tabs>

## Constellations

import Constellation from '@site/src/components/char/Constellation'

<Tabs queryString="constellation">
<TabItem value='c1' label='C1'>
<Constellation char={char} constellation={1} />
</TabItem>

<TabItem value='c2' label='C2'>
<Constellation char={char} constellation={2} />
</TabItem>

<TabItem value='c3' label='C3'>
<Constellation char={char} constellation={3} />
</TabItem>

<TabItem value='c4' label='C4'>
<Constellation char={char} constellation={4} />
</TabItem>

<TabItem value='c5' label='C5'>
<Constellation char={char} constellation={5} />
</TabItem>

<TabItem value='c6' label='C6'>
<Constellation char={char} constellation={6} />
</TabItem>
</Tabs>

## Full Talent Values

import TalentsFull from '@site/src/components/char/TalentsFull'

<TalentsFull char={char}/>

## Evidence Vault

<Card item={require('../../evidence/characters/pyro/arlecchino.md')} />
