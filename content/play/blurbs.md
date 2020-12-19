---
title: Triumph Character Blurbs
date: 2019-03-31
draft: false
navSection: play
weight: 4
---

Here are all the blurbs for the characters available to play in *Triumph*.
These are intended as a brief sketch; a fuller character sheet will be
available closer to the event, with more details about motivations and
relationships.

<!--more-->

*Note:* You may not wish to read the blurbs for characters with secrets unless
you are considering playing a character of that type. Those marked ‡ have deep
secrets and, on the whole, are not quite what they seem. Those marked † have
secrets of a lesser nature.

Names of other characters in bold indicate potential romantic relationships,
if both players consent to play that but please note that other romances are
possible and, if both players consent, encouraged.

If you prefer, you can download this listing <a href="/play/Triumph Character Blurbs.pdf">as a pdf</a>.

<style>
  .triumph_list { background-color: #f2bc29 !important }
  .mentor_list { background-color: #2fa1f7 !important }
  .capital_list { background-color: #ed94ff !important }
</style>

<script>
function sortTable(sortBy) {
  var table, rows, switching, i, x, y, shouldSwitch;
  table = document.getElementById("charlist");
  switching = true;

  while (switching) {
    switching = false;
    rows = table.rows;

    for (i = 0; i < (rows.length - 1); i++) {
      shouldSwitch = false;
      x = rows[i].getElementsByTagName("td")[0];
      y = rows[i + 1].getElementsByTagName("td")[0];

      xVal = x.getAttribute("data-" + sortBy);
      yVal = y.getAttribute("data-" + sortBy);

      if (xVal === yVal) {
        xVal = x.getAttribute("data-name");
        yVal = y.getAttribute("data-name");
      }

      if (xVal > yVal) {
        shouldSwitch = true;
        break;
      }
    }

    if (shouldSwitch) {
      rows[i].parentNode.insertBefore(rows[i + 1], rows[i]);
      switching = true;
    }
  }
}
</script>

<button onclick="sortTable('index')">Index</button>
<button onclick="sortTable('name')">Alphabetical</button>
<button onclick="sortTable('role')">Role</button>
<button onclick="sortTable('canton')">Canton</button>

<table id="charlist">
<tr class="triumph_list">
  <td data-index="01" data-name="kes_gold" data-role="star" data-canton="01">{{< icon "star" >}}{{< icon "bolt" >}}<a href="#kes_gold">Kes Gold</a></td>
  <td>The beloved heir</td>
</tr>
<tr class="triumph_list">
  <td data-index="02" data-name="drew_gold" data-role="star" data-canton="01">{{< icon "star" >}}{{< icon "bolt" >}}<a href="#drew_gold">Drew Gold</a></td>
  <td>Triumph from a poor family</td>
</tr>
<tr class="mentor_list">
  <td data-index="03" data-name="kim_gold" data-role="medal" data-canton="01">{{< icon "medal" >}}{{< icon "bolt" >}}<a href="#kim_gold">Kim Gold</a></td>
  <td>Professional coach</td>
</tr>
<tr class="capital_list">
  <td data-index="04" data-name="amory_gold" data-role="landmark" data-canton="01">{{< icon "landmark" >}}{{< icon "bolt" >}}<a href="#amory_gold">Amory Gold</a></td>
  <td>Triumvir</td>
</tr>
<tr class="capital_list">
  <td data-index="05" data-name="nevin_gold" data-role="landmark" data-canton="01">{{< icon "landmark" >}}{{< icon "bolt" >}}<a href="#nevin_gold">Nevin Gold</a></td>
  <td>Corporate rep</td>
</tr>
<tr class="triumph_list">
  <td data-index="06" data-name="cullen_weaver" data-role="star" data-canton="02">{{< icon "star" >}}{{< icon "feather" >}}<a href="#cullen_weaver">Cullen Weaver</a></td>
  <td>An ordinary Weaver in an extraordinary situation</td>
</tr>
<tr class="triumph_list">
  <td data-index="07" data-name="baylor_weaver" data-role="star" data-canton="02">{{< icon "star" >}}{{< icon "feather" >}}<a href="#baylor_weaver">Baylor Weaver</a></td>
  <td>Troublemaker</td>
</tr>
<tr class="mentor_list">
  <td data-index="08" data-name="memphis_weaver" data-role="medal" data-canton="02">{{< icon "medal" >}}{{< icon "feather" >}}<a href="#memphis_weaver">Memphis Weaver</a></td>
  <td>Weaver of webs</td>
</tr>
<tr class="capital_list">
  <td data-index="09" data-name="jess_weaver" data-role="landmark" data-canton="02">{{< icon "landmark" >}}{{< icon "feather" >}}<a href="#jess_weaver">Jess Weaver</a></td>
  <td>Media Star and MC</td>
</tr>
<tr class="capital_list">
  <td data-index="10" data-name="kelly_weaver" data-role="landmark" data-canton="02">{{< icon "landmark" >}}{{< icon "feather" >}}<a href="#kelly_weaver">Kelly Weaver</a></td>
  <td>Fashionista</td>
</tr>
<tr class="triumph_list">
  <td data-index="11" data-name="gem_fisher" data-role="star" data-canton="03">{{< icon "star" >}}{{< icon "anchor" >}}<a href="#gem_fisher">Gem Fisher</a></td>
  <td>The survivor</td>
</tr>
<tr class="triumph_list">
  <td data-index="12" data-name="cass_fisher" data-role="star" data-canton="03">{{< icon "star" >}}{{< icon "anchor" >}}<a href="#cass_fisher">Cass Fisher</a></td>
  <td>Torn from their beloved</td>
</tr>
<tr class="mentor_list">
  <td data-index="13" data-name="frankie_fisher" data-role="medal" data-canton="03">{{< icon "medal" >}}{{< icon "anchor" >}}<a href="#frankie_fisher">Frankie Fisher</a></td>
  <td>Team worker</td>
</tr>
<tr class="capital_list">
  <td data-index="14" data-name="bowie_fisher" data-role="landmark" data-canton="03">{{< icon "landmark" >}}{{< icon "anchor" >}}<a href="#bowie_fisher">Bowie Fisher</a></td>
  <td>Security</td>
</tr>
<tr class="capital_list">
  <td data-index="15" data-name="arden_fisher" data-role="landmark" data-canton="03">{{< icon "landmark" >}}{{< icon "anchor" >}}<a href="#arden_fisher">Arden Fisher</a></td>
  <td>Praisesinger</td>
</tr>
<tr class="capital_list">
  <td data-index="16" data-name="trebizond_spretzel" data-role="landmark" data-canton="03">{{< icon "landmark" >}}{{< icon "anchor" >}}<a href="#trebizond_spretzel">‡Trebizond Spretzel</a></td><td>???</td>
</tr>
<tr class="triumph_list">
  <td data-index="17" data-name="mal_spade" data-role="star" data-canton="04">{{< icon "star" >}}{{< icon "gem" >}}<a href="#mal_spade">Mal Spade</a></td>
  <td>Framed for a heinous crime</td>
</tr>
<tr class="triumph_list">
  <td data-index="18" data-name="lin_spade" data-role="star" data-canton="04">{{< icon "star" >}}{{< icon "gem" >}}<a href="#lin_spade">Lin Spade</a></td>
  <td>Jailed for heretical views</td>
</tr>
<tr class="mentor_list">
  <td data-index="19" data-name="everest_spade" data-role="medal" data-canton="04">{{< icon "medal" >}}{{< icon "gem" >}}<a href="#everest_spade">Everest Spade</a></td>
  <td>Top dog</td>
</tr>
<tr class="capital_list">
  <td data-index="20" data-name="yanik_spade" data-role="landmark" data-canton="04">{{< icon "landmark" >}}{{< icon "gem" >}}<a href="#yanik_spade">Yanik Spade</a></td>
  <td>Gamekeeper</td>
</tr>
<tr class="capital_list">
  <td data-index="21" data-name="filimore_partridge" data-role="landmark" data-canton="04">{{< icon "landmark" >}}{{< icon "gem" >}}<a href="#filimore_partridge">‡Filimore Partridge</a></td><td>???</td>
</tr>
<tr class="triumph_list">
  <td data-index="22" data-name="tov_smith" data-role="star" data-canton="05">{{< icon "star" >}}{{< icon "gavel" >}}<a href="#tov_smith">Tov Smith</a></td>
  <td>Naïve and unfortunate</td>
</tr>
<tr class="triumph_list">
  <td data-index="23" data-name="falc_smith" data-role="star" data-canton="05">{{< icon "star" >}}{{< icon "gavel" >}}<a href="#falc_smith">Falc Smith</a></td>
  <td>Rebel without a clue</td>
</tr>
<tr class="mentor_list">
  <td data-index="24" data-name="brook_smith" data-role="medal" data-canton="05">{{< icon "medal" >}}{{< icon "gavel" >}}<a href="#brook_smith">Brook Smith</a></td>
  <td>Hard bitten, taciturn</td>
</tr>
<tr class="capital_list">
  <td data-index="25" data-name="castor_smith" data-role="landmark" data-canton="05">{{< icon "landmark" >}}{{< icon "gavel" >}}<a href="#castor_smith">Castor Smith</a></td>
  <td>Triumvir</td>
</tr>
<tr class="capital_list">
  <td data-index="26" data-name="indigo_smith" data-role="landmark" data-canton="05">{{< icon "landmark" >}}{{< icon "gavel" >}}<a href="#indigo_smith">‡Indigo Smith</a></td>
  <td>Board Member</td>
</tr>
<tr class="triumph_list">
  <td data-index="27" data-name="ban_wright" data-role="star" data-canton="06">{{< icon "star" >}}{{< icon "atom" >}}<a href="#ban_wright">Ban Wright</a></td>
  <td>Test pilot</td>
</tr>
<tr class="triumph_list">
  <td data-index="28" data-name="jules_wright" data-role="star" data-canton="06">{{< icon "star" >}}{{< icon "atom" >}}<a href="#jules_wright">Jules Wright</a></td>
  <td>Resentful youth</td>
</tr>
<tr class="mentor_list">
  <td data-index="29" data-name="tobin_wright" data-role="medal" data-canton="06">{{< icon "medal" >}}{{< icon "atom" >}}<a href="#tobin_wright">Tobin Wright</a></td>
  <td>Brains are better than brawn</td>
</tr>
<tr class="capital_list">
  <td data-index="30" data-name="goura_wright" data-role="landmark" data-canton="06">{{< icon "landmark" >}}{{< icon "atom" >}}<a href="#goura_wright">Goura Wright</a></td>
  <td>Gamekeeper</td>
</tr>
<tr class="capital_list">
  <td data-index="31" data-name="munroe_wright" data-role="landmark" data-canton="06">{{< icon "landmark" >}}{{< icon "atom" >}}<a href="#munroe_wright">Munroe Wright</a></td>
  <td>Corporate rep</td>
</tr>
<tr class="triumph_list">
  <td data-index="32" data-name="swift_silver" data-role="star" data-canton="07">{{< icon "star" >}}{{< icon "coins" >}}<a href="#swift_silver">Swift Silver</a></td>
  <td>Embezzler and a sneak thief</td>
</tr>
<tr class="triumph_list">
  <td data-index="33" data-name="blair_silver" data-role="star" data-canton="07">{{< icon "star" >}}{{< icon "coins" >}}<a href="#blair_silver">Blair Silver</a></td>
  <td>Athlete and team player</td>
</tr>
<tr class="mentor_list">
  <td data-index="34" data-name="silence_silver" data-role="medal" data-canton="07">{{< icon "medal" >}}{{< icon "coins" >}}<a href="#silence_silver">Silence Silver</a></td>
  <td>Wheeler dealer</td>
</tr>
<tr class="capital_list">
  <td data-index="35" data-name="milan_silver" data-role="landmark" data-canton="07">{{< icon "landmark" >}}{{< icon "coins" >}}<a href="#milan_silver">Milan Silver</a></td>
  <td>PA to a Triumvir</td>
</tr>
<tr class="capital_list">
  <td data-index="36" data-name="ellis_silver" data-role="landmark" data-canton="07">{{< icon "landmark" >}}{{< icon "coins" >}}<a href="#ellis_silver">Ellis Silver</a></td>
  <td>Corporate rep</td>
</tr>
<tr class="triumph_list">
  <td data-index="37" data-name="red_ward" data-role="star" data-canton="08">{{< icon "star" >}}{{< icon "shield-alt" >}}<a href="#red_ward">Red Ward</a></td>
  <td>Disgraced NCO</td>
</tr>
<tr class="triumph_list">
  <td data-index="38" data-name="ripley_ward" data-role="star" data-canton="08">{{< icon "star" >}}{{< icon "shield-alt" >}}<a href="#ripley_ward">Ripley Ward</a></td>
  <td>Professional soldier</td>
</tr>
<tr class="mentor_list">
  <td data-index="39" data-name="strega_ward" data-role="medal" data-canton="08">{{< icon "medal" >}}{{< icon "shield-alt" >}}<a href="#strega_ward">Strega Ward</a></td>
  <td>Someone with a target on their back</td>
</tr>
<tr class="capital_list">
  <td data-index="41" data-name="paris_ward" data-role="landmark" data-canton="08">{{< icon "landmark" >}}{{< icon "shield-alt" >}}<a href="#paris_ward">Paris Ward</a></td>
  <td>Corporate Rep</td>
</tr>
<tr class="triumph_list">
  <td data-index="42" data-name="jan_bright" data-role="star" data-canton="09">{{< icon "star" >}}{{< icon "sun" >}}<a href="#jan_bright">Jan Bright</a></td>
  <td>A lover, not a fighter</td>
</tr>
<tr class="triumph_list">
  <td data-index="43" data-name="cal_bright" data-role="star" data-canton="09">{{< icon "star" >}}{{< icon "sun" >}}<a href="#cal_bright">Cal Bright</a></td>
  <td>Focussed and determined</td>
</tr>
<tr class="mentor_list">
  <td data-index="44" data-name="rain_bright" data-role="medal" data-canton="09">{{< icon "medal" >}}{{< icon "sun" >}}<a href="#rain_bright">†Rain Bright</a></td>
  <td>Dying from consequences of past actions</td>
</tr>
<tr class="capital_list">
  <td data-index="45" data-name="sigil_bright" data-role="landmark" data-canton="09">{{< icon "landmark" >}}{{< icon "sun" >}}<a href="#sigil_bright">‡Sigil Bright</a></td>
  <td>PA and voice of absent Triumvir</td>
</tr>
<tr class="capital_list">
  <td data-index="46" data-name="sky_bright" data-role="landmark" data-canton="09">{{< icon "landmark" >}}{{< icon "sun" >}}<a href="#sky_bright">‡Sky Bright</a></td>
  <td>Bodyguard to Triumvir</td>
</tr>
<tr class="triumph_list">
  <td data-index="47" data-name="arles_cropper" data-role="star" data-canton="10">{{< icon "star" >}}{{< icon "carrot" >}}<a href="#arles_cropper">Arles Cropper</a></td>
  <td>A martyr for the family</td>
</tr>
<tr class="triumph_list">
  <td data-index="48" data-name="bel_cropper" data-role="star" data-canton="10">{{< icon "star" >}}{{< icon "carrot" >}}<a href="#bel_cropper">Bel Cropper</a></td>
  <td>A reckless volunteer</td>
</tr>
<tr class="mentor_list">
  <td data-index="49" data-name="barley_cropper" data-role="medal" data-canton="10">{{< icon "medal" >}}{{< icon "carrot" >}}<a href="#barley_cropper">Barley Cropper</a></td>
  <td>Jaded and lonely but not without hope</td>
</tr>
<tr class="capital_list">
  <td data-index="50" data-name="hemmy_cropper" data-role="landmark" data-canton="10">{{< icon "landmark" >}}{{< icon "carrot" >}}<a href="#hemmy_cropper">Hemmy Cropper</a></td>
  <td>Gamekeeper</td>
</tr>
<tr class="triumph_list">
  <td data-index="51" data-name="briar_fletcher" data-role="star" data-canton="11">{{< icon "star" >}}{{< icon "leaf" >}}<a href="#briar_fletcher">Briar Fletcher</a></td>
  <td>The great hunter</td>
</tr>
<tr class="triumph_list">
  <td data-index="52" data-name="jaz_fletcher" data-role="star" data-canton="11">{{< icon "star" >}}{{< icon "leaf" >}}<a href="#jaz_fletcher">Jaz Fletcher</a></td>
  <td>The naïve idealist</td>
</tr>
<tr class="mentor_list">
  <td data-index="53" data-name="sam_fletcher" data-role="medal" data-canton="11">{{< icon "medal" >}}{{< icon "leaf" >}}<a href="#sam_fletcher">Sam Fletcher</a></td>
  <td>Killed their lover in the Games</td>
</tr>
<tr class="capital_list">
  <td data-index="54" data-name="september_fletcher" data-role="landmark" data-canton="11">{{< icon "landmark" >}}{{< icon "leaf" >}}<a href="#september_fletcher">September Fletcher</a></td>
  <td>PA to Triumvir</td>
</tr>
<tr class="triumph_list">
  <td data-index="55" data-name="syd_piper" data-role="star" data-canton="12">{{< icon "star" >}}{{< icon "drum" >}}<a href="#syd_piper">Syd Piper</a></td>
  <td>Musical prodigy</td>
</tr>
<tr class="triumph_list">
  <td data-index="56" data-name="cory_piper" data-role="star" data-canton="12">{{< icon "star" >}}{{< icon "drum" >}}<a href="#cory_piper">Cory Piper</a></td>
  <td>Clown</td>
</tr>
<tr class="mentor_list">
  <td data-index="57" data-name="gentry_piper" data-role="medal" data-canton="12">{{< icon "medal" >}}{{< icon "drum" >}}<a href="#gentry_piper">‡Gentry Piper</a></td>
  <td>Haunted by their secret</td>
</tr>
<tr class="capital_list">
  <td data-index="58" data-name="charleston_piper" data-role="landmark" data-canton="12">{{< icon "landmark" >}}{{< icon "drum" >}}<a href="#charleston_piper">Charleston Piper</a></td>
  <td>MC</td>
</tr>
<tr class="capital_list">
  <td data-index="59" data-name="pip_piper" data-role="landmark" data-canton="12">{{< icon "landmark" >}}{{< icon "drum" >}}<a href="#pip_piper">Pip Piper</a></td>
  <td>Assistant to the Media</td>
</tr>
<tr class="capital_list">
  <td data-index="60" data-name="stafford_piper" data-role="landmark" data-canton="12">{{< icon "landmark" >}}{{< icon "drum" >}}<a href="#stafford_piper">Stafford Piper</a></td>
  <td>Gamekeeper</td>
</tr>
<tr class="capital_list">
  <td data-index="61" data-name="hamilton_maddox" data-role="landmark" data-canton="13">{{< icon "landmark" >}}{{< icon "chess-king" >}}<a href="#hamilton_maddox">†Hamilton Maddox</a></td>
  <td>Bored corporate heir</td>
</tr>
<tr class="capital_list">
  <td data-index="62" data-name="arundel_cambourne" data-role="landmark" data-canton="13">{{< icon "landmark" >}}{{< icon "chess-king" >}}<a href="#arundel_cambourne">†Arundel Cambourne</a></td>
  <td>Shallow socialite</td>
</tr>
<tr class="capital_list">
  <td data-index="63" data-name="zephyr_baradras" data-role="landmark" data-canton="13">{{< icon "landmark" >}}{{< icon "chess-king" >}}<a href="#zephyr_baradras">†Zephyr Baradras</a></td>
  <td>Poor little rich kid</td>
</tr>
<tr class="capital_list">
  <td data-index="64" data-name="lennox_downwater" data-role="landmark" data-canton="13">{{< icon "landmark" >}}{{< icon "chess-king" >}}<a href="#lennox_downwater">†Lennox Downwater</a></td>
  <td>Corporate heir and adrenaline junkie</td>
</tr>
<tr class="capital_list">
  <td data-index="65" data-name="caroly_wendelsmith" data-role="landmark" data-canton="13">{{< icon "landmark" >}}{{< icon "chess-king" >}}<a href="#caroly_wendelsmith">Caroly Wendelsmith</a></td>
  <td>Child of a Triumvir</td>
</tr>
<tr class="capital_list">
  <td data-index="66" data-name="porphyry_mendleson" data-role="landmark" data-canton="13">{{< icon "landmark" >}}{{< icon "chess-king" >}}<a href="#porphyry_mendleson">†Porphyry Mendleson</a></td>
  <td>The richest person in the Eternal City</td>
</tr>
</table>

## On Relations

Full relationships for the characters will appear in the finalized sheets. We
are trying to keep these teasers short so there isn’t space to go into any
depth about them. It is safe to assume that everyone living in the Eternal
City has some knowledge of each other (depending on how long they have been
there). Characters from the provinces who have been together in Canton 12 or
who reside in the Eternal City also tend to know each other. Expats always
tend to hang out in the same places and hand out advice (both good and bad) on
how to survive in their adoptive environment.

Similarly, everyone knows something about the famous characters… The
Triumvirs, the Media stars and, to a lesser extent, the Victors. The mentors
all know each other, and this will be reflected in their full descriptions.

## On Secrets

Several characters have secrets — we’ve done our best to hint at them without
revealing them fully here. In the interactive table we’ve indicated which
characters have secrets you, the player, may prefer not to know.

---

# {{< icon "bolt" >}} Jupiter’s Children

## <a name="kes_gold"></a>{{< icon "star" >}} Triumph Kes Gold

*The beloved heir*

### What you hope for

To win the Games and bring honour to your canton

### How you got here

You believe in the Imperium. You believe in the system. You worked and trained
damned hard to earn your place at the Games and you’re determined to do your
Canton proud. The Fortunate Canton is, after all, the best place to be born.
Most people’s families would be proud and honoured to have one of their own
represent the Canton. Your family, on the other hand, whilst wealthy and
successful enough to promote you, appear to find your participation in the
Games a source of great distress. Which is downright weird. Everyone else in
the Canton supports you.

The partner you trained with failed the selection. You can’t entirely regret
that; you’d become close and it would have been upsetting to have had to kill
them. It could have put you off your stroke. The other Triumph from your
Canton is someone you don’t know so well. You think their mother was a cleaner
or a waitress or something. Not your class of person at all.

---

## <a name="drew_gold"></a>{{< icon "star" >}} Triumph Drew Gold

*The Triumph from humble origins*

### What you hope for

To survive and return to your loved ones

### How you got here

Not everyone from canon 1 is born with a silver spoon in their mouth. Your
father was a junior schoolteacher — you don’t really remember him — he died
when you were young of some kind of cancer. Your mother didn’t like to talk
about it. She worked as a cleaner, keeping house for rich people and when she
was not at work she was busy looking after your younger siblings. Despite your
relative poverty, you benefitted from a Canton 1 education and, through dint
of hard work got a scholarship to the Academy. There you kept your head down
and trained hard, though you were often the butt of jokes made by those from
‘worthier’ backgrounds — those whose families were able to sponsor their
studies. All except for one special person who became your lover.

No one was more surprised than you when you made the selection for the Games.
Now you have a chance to make a name for yourself and provide for your family.
Which is all you ever wanted. Well, that is one way of looking at it. The
whole thing has been very confusing. You miss your family and your lover, and
worry that you will never get back to them. The Games, after all, have only
one Victor.

---

## <a name="kim_gold"></a>{{< icon "medal" >}} Mentor Kim Gold

*The professional mentor*

### What you hope for

Another Victor for your Canton

### How you got here

The fortunate Canton has a good record at the Games, and you are one of seven
Victors. Unlike some Cantons who always give the same Victor with the job of
mentoring the new Triumphs, Jupiter tends to share the work around. This is
good, it means the mentors are always fresh. The six of you get together (the
seventh Victor died of over-indulgence three years ago) and decide who is the
best match with the current crop of candidates. A bureaucratic process,
perhaps, but that’s what the fortunate Canton are good at.

You enjoy the Games. You like seeing your mentees win! And you fully intend
one of them to win this time. They are both solid Victor material. They don’t
seem to have taken an immediate liking to each other, which is not a bad
thing, problems arise when they keep trying to rescue each other. The big
worry this year is Ari’s family. They seem determined that Ari should survive
the Games. If that is by winning, all well and good. If it’s by some form of
illegal abstraction… it would do your reputation no good at all. Their father
would pay generously if you could arrange to save his child, but you don’t
need the money. It’s not as if any sensible Victor is short of a few thousand
credits. And the penalty for corrupting the Games is death.

You think of yourself as a professional. Your Triumphs must think of
themselves as professionals. You will encourage them to head up a team, which
means they need to find other Triumphs to join them. You will use your
relationships with the other mentors to help with this.

---

## <a name="amory_gold"></a>{{< icon "landmark" >}} Triumvir Amory Gold

*Everything is for the best in the best of all possible worlds and the Imperium
is, beyond a doubt, the best of all possible worlds.*

### What you hope for

Appreciation from the masses you serve.

### How you got here

You were born in Canton 1, rose through the ranks, got residency in the
Eternal City and through hard work and dedication gained enough support from
the powerful to be elected as a Triumvir. The system of governance may not be
perfect, but it is the best that could be, and improves year on year. You have
worked hard to improve it. You genuinely want what is best for the Imperium
and all its citizens — rich and poor.

Sometimes you have to make harsh decisions. That is the nature of rulership.
It’s difficult and often costs you your sleep at night, but you always strive
to do what is best. Your past mistakes haunt you, but you can’t let that
interfere with official duties. You try to listen to everyone who petitions
you, but there are a great many of them and you rely on your personal
assistant, Milan Silver, to screen them for you.

You believe that the populace loves you and would be shocked to learn of
anyone who did not admire you or believe that the Imperium acts in the best
interests of all its citizens. You are willing to listen to tales of hardship
and do your best to correct these isolated glitches in the system. Are there
rebels? What is it they don’t like? Clearly they cannot understand the true
situation!

---

## <a name="Nevin_gold"></a>{{< icon "landmark" >}} Nevin Gold

*Skilled and savvy corporate rep out to impress the boss*

### What you hope for

A promotion

### How you got here

You came to the Eternal City quite recently from Canton 1. There your skills
as a Project Manager and Negotiator brought you to the attention of Cambourne
Fast Foods corporation. Apart from working closely with the production teams
from Cantons 3 and 10, you have important relationships with Venus as her
denizens create the advertisements on which Cambourne profits depend. It’s
demanding work and you feel very honoured to be representing the Corporation
at this year’s Games. Do well and you could get promoted, do badly and you
might end up back in your native Canton.

Your job here is twofold. Most importantly, you have to ensure proper product
placement. Packs of delicious Camborne products must appear at some point
during every interview. If the Triumphs praise the fish fingers or the
instant-heat apple turnovers you are in a position to reward them with
delicious food drops. Oh, you know that once they get out in the field,
they’re not going to care much about what the food tastes like, as long as it
fills their bellies and gives them strength. But you hope to play on the ease
of preparation angle. The Triumphs who please you will just need to add water
whilst those who do not help with product placement will have to cook their
food over an attention-attracting open fire or eat it raw. The hygienically
packed product is also proof against poisoning, something you understand has
been a problem at previous contests. You would like to know more about that —
it would help you to convince the Triumphs of the desirability of your
product.

It’s surprising that Cambourne’s major rivals, Armwood Delicacies, do not have
any open representation here although you’ve noticed their products being
served at every official dinner.

You have yet to form relationships with anyone from the Eternal City but,
clearly, the right sort of relationships could benefit you greatly.

---

# {{< icon "feather" >}} Juno’s Children

## <a name="cullen_weaver"></a>{{< icon "star" >}} Triumph Cullen Weaver

*An ordinary weaver in an extraordinary situation*

### What you hope for

To be with your beloved or, at least, to be able to talk to them

### How you got here

Usually the Council of Elders select troublemakers to be Triumphs, though some
years they have chosen to sacrifice one of the exceptionally talented. You
have no idea why they selected you. You are, honestly, no one special. You’re
not exceptionally talented but neither are you clumsy. You just keep your head
down in the weaving workshop and produce work of an acceptable standard. At
least that is what you did before your selection. It all came as a bit of a
shock.

Back in your home canton you spent a lot of time with your beloved. You and
they had hoped to make a life together, though their family, who are well
connected, did not approve. Your partner even went so far as to suggest that
it was their disapproval that led to your selection. You find it hard to
believe anyone could be so mean.

Your beloved does not want to lose you and is determined you should be the
Victor at these Games so you can bring them to the Eternal City and the two of
you can be together again. The problem is that your Canton has only ever
produced two Victors. One of those is your mentor and they are contradicting
everything your lover taught you.

---

## <a name="baylor_weaver"></a>{{< icon "star" >}} Triumph Baylor Weaver

*A rebel and a troublemaker*

### What you hope for

To win the games or, at least, to enjoy your brief experience of the Eternal City

### How you got here

You know full well why the Elders selected you for the Games. You’ve always
been a rebel and a troublemaker. If they told you to weave red, you’d weave
blue. But blue of the most wonderful and original shade. The plain fact is
that the Elders never really recognised your talent. You should have gone to
Venus’ Canton to design costumes for the stars. That would be a fitting task
for you. Instead they sent you to the Eternal City to be out of the way.
Probably to die. Whatever. Your rebellious streak tells you that the best way
to defy the Elders here would be NOT to die. You are going to do your best to
win these Games.

You’ve fallen head over heels in love with the Eternal City and the people who
live here. It’s so different from the boring way things are back home! So,
whilst it goes against the grain, you’re trying hard to do exactly as your
mentor instructs. They say you need to develop a killer instinct. You find it
helps to regard your rival Triumphs as some particularly oppressive Elder or
Teacher. That way you can hate them. That way you can imagine trying to kill
them. You need to practice with weapons, and you need to gain the favour of
influential people…

---

## <a name="memphis_weaver"></a>{{< icon "medal" >}} Mentor Memphis Weaver

*The weaver of webs*

### What you hope for

One of your Triumphs to survive

### How you got here

Yours is a tough job. There have only ever been two Victors from Canton 2. You
won your crown by weaving webs — webs of netting and webs of deceit — to
entrap the other Triumphs. Cameron, the other Victor from your canton won his
by being patient, lying in wait for the others and lashing out at them as they
passed him. He’s gone now. Couldn’t cope with life in the Eternal City —
couldn’t cope with being away from his friends and family back home. He killed
himself. Now you remain and you have to teach these two Triumphs how to
survive in the arena.

You will do your best for them. Cullen is steady and determined but lacks the
killer instinct, far too prone to pull their blows or looking over their
shoulder to check with you that they are doing everything right. Baylor has
the spark but lacks concentration. You have real doubts either could survive
on their own ability. There is some fierce competition this year. Both
Triumphs from 1 are top class and one of the Triumphs from 8 seems to have
everything it takes. You are going to have to use all your deceitful and wily
nature to persuade those in power to favour your Triumphs and supply them with
the weapons and conditions they need to survive.

You’ve been cultivating Jess Weaver in the hope that they will be generous to
your Triumphs and help to make them more attractive to sponsors.

---

## <a name="jess_weaver"></a>{{< icon "landmark" >}} Jess Weaver

*The up and coming media star*

### What you hope for

To prove yourself

### How you got here

You were born and received your primary education in Canton 2. A talented
actor with journalistic talent, you won a scholarship to film school in Canton
12 from whence you recently graduated. You’ve done a couple of shows which got
complimentary reviews, but this is your first really big assignment. You are
proud and determined to do well but this is a huge challenge. Charleston Piper
has been your role model for as long as you remember, and you would love to
learn from them. They do, however, seem rather impatient. Still, you know you
have a lot to learn and you are trying to make the best possible impression on
your fellow MC as well as on the public.

It is a huge honour to interview the Triumphs and their mentors. You have
heard stories of media stars taking bribes to favour one Triumph over another,
but you are sure this is just rumour put around by malcontents. In any case,
this is your big chance — do well here and the world is your oyster. Mess up
and the world will forget you in an instant. Mess up really badly and they
might even send you back to Canton 2 which would be shameful — how could you
explain yourself to your family and friends if that were to happen?

You are relying on your PA, Pip Piper, to advise you on etiquette and how to
handle the unfamiliar atmosphere of the Eternal City, but they do seem rushed
off their feet. You would like to support them more. You are part of the loose
social group of those who went to Canton 12 from elsewhere. Kelly Weaver has
been a close friend and you are happy to see them here. Mentor Memphis Weaver
seems keen to cultivate you but whether that’s flirtation, genuine friendship
or the hope that you will promote their Triumphs is currently unknown.

---

## <a name="kelly_weaver"></a>{{< icon "landmark" >}} Kelly Weaver

*Fashionista: Assisting the Games with everything related to fashion*

### What you hope for

Gossip. And, maybe, romance

### How you got here

You were born and raised in Canton 2 where you discovered your flair for
clothing design. That got you sent to Venus’ Canton to work on costuming.
Today you are in the Eternal City to assist the media in covering all kinds of
fashion issues. You will be commenting on the way the Triumphs present
themselves, ensuring their costuming meets both their needs and those of the
camera crews. You will provide reports on the fashions worn by the glitterati
in attendance. Not a stitch escapes your knowledgeable and critical gaze.

After fabrics and fashion, your second love is gossip. You don’t go in front
of the cameras yourself, but you love to provide the MCs and their assistant
with juicy material. Because you are not directly associated with the media,
people open up to you more than they might if they thought their confessions
would get an immediate public airing. And you can sneak around, waiting for
people to reveal themselves.

You are part of the loose social group of those invited to Canton 12 from
elsewhere. You don’t know Arden Fisher so well, but you were friends with an
ex-lover of theirs and know how much they would like to get back together. You
and Jess Weaver were close during your time in Canton 12 and you’re happy to
see them here. You have observed that Charleston Piper is trying to undermine
your friend and you will support Jess in any way you can, by providing them
with the juiciest bits of gossip that fall into your open hands.

---

# {{< icon "anchor" >}} Neptune’s Children

## <a name="gem_fisher"></a>{{< icon "star" >}} Triumph Gem Fisher

*The survivor*

### What you hope for

To survive by learning the weaknesses of your opponents

### How you got here

You were born and raised in Canton 3. The sea is a cruel mistress and many of
your friends and family drowned, sailing out in storms when they would have
been better off staying home by the fire. Sailing out to bring home a catch,
to make a living for their loved ones. You’ve been working the boats since you
were six. It’s made you strong, tough, and quick. You may not have the benefit
of the kinds of training they get with Mars or Jupiter, but you are sure you
can give those coddled Triumphs a run for their money. You are a survivor.
You’ve swum ashore from boats when the others all drowned.

Cass, your fellow Triumph is a ball of misery, unlikely to be of much help.
You don’t regret that too much, you are, after all, going to have to kill all
the other Triumphs if you are to survive. And you are a survivor. That is what
you have going for you. Now you just have to concentrate as hard as you can on
your training and try to learn the weaknesses of your opponents.

---

## <a name="cass_fisher"></a>{{< icon "star" >}} Triumph Cass Fisher

*Ripped from a perfect life with their beloved.*

### What you hope for

To be reunited with your beloved

### How you got here

You were born and raised in Canton 3. Not in the lap of luxury, but you and
your family nearly always had enough to eat and, if you didn’t, the neighbours
would see you right. Everything was going so well! You and your childhood
sweetheart saved up enough to lease a stall on the fish market in a pleasant
district near to both your families. You married and both of you looked
forward so much to running the business and raising children. Then your name
came out of the lottery.

You were devastated. You tried to put on a brave face for your spouse and the
rest of your family and friends but here in the Eternal City you feel so
alone. Your mentor and fellow Triumph try to be sympathetic but can’t help
showing their frustration at your continuing misery. Now you have to smile for
the cameras when all you want is your old life back. Is there any escape in
sight for you? Will you ever see your beloved again?

---

## <a name="frankie_fisher"></a>{{< icon "medal" >}} Mentor Frankie Fisher

*Believer in Fortuna and teamwork*

### What you hope for

One of your Triumphs to survive

### How you got here

Some Cantons select their best to represent them at the Games, some chose
their worst as a means of being rid of them. The Fishers draw lots, showing
their faith in Fortuna. You are one of three Victors from Neptune’s Canton and
the fact that your Canton has produced so many is testament to the power of
Fortuna. The three of you draw lots to see who will mentor in any given year,
and this year the lot fell to you. You’ve discussed strategy with your fellows
ahead of time and you know they will be cheering you on. The problem with
Triumphs from your Canton is that they tend to be very independent minded and
underestimate the importance of teamwork. So, apart from the actual training
and advice and pushing for sponsors etc. etc., a large part of your work will
be talking to the other mentors and getting your Triumphs into powerful teams.

The simple fact is that there is only one way to win the Games and that is to
outlive all the other Triumphs. Fortuna has sent you a mixed pair of Triumphs
this year. Cass is in constant misery. You are not sure whether you can
motivate them. You fear they will be amongst the first to die unless, of
course, you can persuade the other Triumphs they are not a threat. Gem is
promising. Very promising. Reminds you a lot of your own attitude and that of
your fellow Victors.

Bowie Fisher is a friend and has asked you to let them know if you get any
hint of dissent — they say people are more likely to confide in you than they
are to confide in a security guard. You’re not sure how you feel about that.
You’re here to look after your Triumphs, not to be a spy. But as you’ll be
talking to the other mentors anyway, there seems to be no harm in helping your
friend out with this task.

---

## <a name="bowie_fisher"></a>{{< icon "landmark" >}} Bowie Fisher

*Security chief alert for signs of trouble*

### What you hope for

A smooth-running Games with no disruptions.

### How you got here

You were born and raised in Canton 3. This made you hardy and wary. A while
back you received an invitation to the Eternal City to work with the security
forces. Too much like grunt work for any of their own kids and, whilst the
majority of your colleagues originate from Cantons 4 and 9, there is a move to
ensure that every Canton has representation on street level if not necessarily
in the higher echelons.

You are here to provide security at the Games. Any issues that break out are
yours to deal with. You don’t have to go diving in yourself, you have plenty
of staff to deal with any issues, but it’s your job to spot issues before they
get on camera and get any problems closed down. You report to Triumvir Amory
Gold and you often work through their PA whom you trust to get information to
whoever needs it. You understand that Porphyry Mendleson is the top security
boss, though you have never met them before.

On top of this task, you are on the lookout for any dissenters who might seek
to disrupt the Games or undermine the Imperium. This is one of those rare
occasions where people from all the Cantons get the chance to meet openly and
the security forces consider it likely that rebels will try to make contact
with sympathisers here. You’ve asked your friend, Mentor Frankie Fisher, to
let you know if they hear anything.

---

## <a name="arden_fisher"></a>{{< icon "landmark" >}} Arden Fisher

*The praisesinger*

### What you hope for

To determine your own future and, maybe, get back to your first love

### How you got here

You were born in Canton 3. Your family were poor but not desperately so and
always gave to those worse off than themselves. From your earliest years you
showed a talent for art and your family and teachers encouraged this. You were
a great admirer of the Imperium and the system and longed to travel to the
Eternal City. By your late teens, you were sent to Canton 12 which you hated.
You found the residents far too superficial though you did find your first
love there and, though you have had other lovers since, you still miss them.

You had to leave your first love when you achieved your lifelong ambition and
received the call to reside in the Eternal City. Here you create art in praise
of the Imperium and its most important citizens. Of late, however, you have
become disillusioned. Close proximity to the centre of power has shown you the
corruption that lies beneath the glittering surface. You still create paeans
of praise for your patrons, but you have come to despise yourself for your own
hypocrisy.

You understand that your Art could undermine the status quo as easily as it
props it up. You have heard rumours of a nascent rebel movement but understand
they are reluctant to approach you due to your reputation for singing the
praises of the Imperium.

Most of those who are invited to the Carnival from elsewhere know each other.
It’s a loose social group. So, you have a vague acquaintance with Jess and
Kelly Weaver. Kelly, in particular, was friendly with your first love… Might
they be able to put you in touch again?

---

## <a name="trebizond_spretzel"></a>{{< icon "landmark" >}} Trebizond Spretzel

*Ambitious undercover corporate rep, posing as a vapid socialite*

### What you hope for

An invitation to remain in the Eternal City

### How you got here

You were born and raised in Canton 3. There you worked in food processing and
your talent for inventing new ways to present and preserve delicate produce
came to the attention of Armwood Delicacies, a major corporation specialising
in fancy foods. They have invited you to attend the Games as their undercover
representative. If you do well, a more permanent position with the corporation
is on offer. If you do really well, that position might be based in the
Eternal City itself. Sure, if you got that, you’d be leaving your friends and
family back in Neptune’s Canton, but you’re not that attached to the place
and, anyway, there’s always the possibility of bringing others to live with
you if you get promoted high enough. You’ve always been ambitious, and this is
an exciting opportunity.

Armwood has provided you with a fashionable outfit and spent some time working
with you on your accent and speech patterns. You are posing as a vapid
socialite, but your real purpose is to undermine Cambourne’s efforts to use
the Games to publicize their disgusting products. They will, no doubt, be
offering drops of their instant goop to the Triumphs. Armwood foods are not
suitable for that — it would wreck the careful presentation. There is, of
course, nothing to stop you using the samples you carry to tempt the jaded
appetites of those who dwell in the Eternal City. Others have ensured that
Armwood products are on every table set to entertain the Triumphs.

Arundel Cambourne seems to enjoy your wares and to have taken a liking to you.
They have taken you under their wing and you are learning from them how to
pose as a socialite in the Eternal City. Which is a bit awkward as your task
here is to undermine their family corporation.

---

# {{< icon "gem" >}} Pluto’s Children

## <a name="mal_spade"></a>{{< icon "star" >}} Triumph Mal Spade

*Framed for a horrible crime*

### What you hope for

To clear your name

### How you got here

You were born and raised in Pluto’s Canton. You once worked as a clerk in an
office associated with a coal mine. It was a good enough life, considering.
You were grateful that you did not have to work in the mines because people
who work in the mines constantly face the threat of death or life changing
injury. Then, some years back, you found yourself in jail, serving a life
sentence. Accused of a heinous crime, the jury found you guilty. You can’t
blame them. You’ve seen the pictorial evidence. It makes you feel sick just to
think of it.

The mass of evidence ranged against you almost made you believe that you
committed the crime. But you didn’t. You know that you didn’t.

Being a Triumph is your only chance for parole. Though that doesn’t matter so
much. More important, it is your only chance to clear your name. You would,
honestly, rather die with honour in the Games, with your name cleared than
have people go on believing that you committed that terrible crime.

---

## <a name="lin_spade"></a>{{< icon "star" >}} Triumph Lin Spade

*Rebel, jailed for political views*

### What you hope for

To change the corrupt system

### How you got here

You were born and raised in Canton 4 where men and women go down the coal
mines and, even if they aren’t horribly mutilated or dead in some accident,
have a vastly reduced life expectancy due to the conditions they suffer. The
bosses have it easy. Them and the idle rich in the Eternal City who profit
from the fruits of the labours of others. The Games aren’t even half of it.
Sure, it’s bad enough that the toffs get their rocks off watching the proles
slaughter each other on an annual basis, but it’s what goes on in the Cantons,
day after day, week after week that really gets you angry. You are constantly
angry, and you are not the type to keep quiet about injustice.

Which is what got you thrown into jail. Where you would have rotted had you
not grabbed at the chance to come to the Eternal City and make your points to
the Triumvirs and their lackeys in person. Of course, it would be good to
vindicate yourself by winning the Games but, if you end up being a martyr to
the cause, that’s still better than rotting in jail for the rest of your
natural life. You believe there are those here who are sympathetic to the
rebel cause and you are determined to locate them and work with them.

You are disgusted that your fellow Triumph, Mal, is a notorious criminal. Your
mentor has explained that you need to work with them, but it goes against the
grain.

---

## <a name="everest_spade"></a>{{< icon "medal" >}} Mentor Everest Spade

*Top dog ex-convict*

### What you hope for

Your Triumph to win through fair means or foul

### How you got here

When you pull a person out of prison and send them to the Games, they have two
huge advantages. First is that jailtime makes them tough (either that or they
give up in despair and die). Second is that they’re desperate. That is why
your Canton has produced 3 Victors, even though their selection methods mean
they don’t always pick the best. Condemned people will always fight for their
lives and that is what you need to do in order to become a Victor. You’ve
discussed this year’s selection with the other two Victors from Pluto, and you
agree you’re in with a good chance. Another plus is that the Yanik, the new
Gamekeeper, is from your Canton. Of course, they’re going to do everything
they can to appear neutral (given that the punishment for bias is death) but
they’re bound to favour their home Canton — it’s only natural. Apart from
which, they’re a friend of yours and you were happy to celebrate their
promotion. You confided in them that you have some evidence to back up your
suspicion about who bribed their predecessor.

When you were in jail back in Pluto’s Canton, you made certain you got to be
top dog. You did that through a combination of bribery, fear and picking
favourites. You employed much the same strategy in the Games and that is how
you got to be a Victor. Having good sponsors helps and you’re working on that
as hard as you can. You hope the other two Victors from your Canton are
working on that as well, behind the scenes.

---

## <a name="yanik_spade"></a>{{< icon "landmark" >}} Gamekeeper Yanik Spade

*Honest explosives expert*

### What you hope for

A good, clean fight. May the worthiest Triumph win.

### How you got here

You were born and raised in Pluto’s Canton. Last year, your expertise with
underground operations and explosives led to a promotion to the Eternal City
as a Gamekeeper. You were, after all, a great fan of the Games so you are
delighted to be here, though still a little overawed by the luxurious
lifestyle of the Eternal City. You know that rumours of corruption are rife
but you’ve managed to hang onto your belief in the fairness of the Imperium,
despite inadvertently uncovering some evidence that those rumours of
corruption have some basis.

For your own part you are determined to be fair to all the Triumphs.
Especially as you know your predecessor was executed for taking bribes.
Everest Spade, (currently mentoring the Triumphs from your Canton) says they
know who did the bribing, though you do find it hard to believe that there is
so much corruption.

You were very wary of Everest at first — all the Triumphs are chosen from the
prison population and it went against the grain to trust a convicted criminal,
but as you got to know them better you became convinced that they had reformed
and started to think of them as a friend. But now they seem to expect you to
favour their own Triumphs…

---

## <a name="filimore_partridge"></a>{{< icon "landmark" >}} Filimore Partridge

*Posing as a gambler from the Eternal City*

### What you hope for

To find out who really hired you, and why.

### How you got here

Until recently you were a prison guard in Canton 4. You couldn’t say you
positively enjoyed the work, but it was better than working in the mines.
Working in the mines can easily get you killed or maimed. Being a prison guard
can get you killed but you can protect yourself against that by keeping
yourself physically and mentally fit (things that do you little good in a mine
collapse and provide no protection from dust or poison in the air). You’re not
100% certain why you received an invitation to the Eternal City, but it’s not
the kind of invitation you can refuse. You were invited by Indigo Smith who
told you they had spotted your talent. Your task here is to act as undercover
security for Triumvir Smith.

It’s clear that Triumvir Smith does not trust the Bodyguard assigned to him
and, truth to tell, there is something odd about that one. You are curious
about the reasons the bodyguard needs watching and why someone on the Board of
Maddox corporation is involved in Triumvir security issues. You reckon, if you
can get to the bottom of that, there might be something in it for you.

Being undercover requires a cover and Indigo hasn’t really specified that for
you. They told you to ‘act like a toff who has a right to be here’, gave you a
fistful of credits and encouraged you to spend them with Lennox Downwater who
is running a book on the Triumphs. The Downwater kid is from the eternal city
and Indigo told you that, if you need any hints on how a native of the Eternal
City would act, ask Lennox quietly and they will explain. Which adds another
level to the mystery. What is the connection between Indigo, Maddox and
Downwater?

---

# {{< icon "gavel" >}} Vulcan’s Children

## <a name="tov_smith"></a>{{< icon "star" >}} Triumph Tov Smith

*Naïve, hardworking, unfortunate*

### What you hope for

To learn more about the Imperium and perhaps even to survive

### How you got here

You were born and raised in Canton 5. Life there is difficult. Everyone has to
work hard to keep up with their quotas in the factories and, if you or a
family member get sick, you fall behind. Nothing you can do about it. And, if
you fall behind, you lose your job or, worse still, be chosen to die in the
Games. And that is what happened to you. Your mother got sick. You had to stay
home to look after her and your younger siblings. Then your mother died and,
apart from dealing with your grief, your younger siblings needed you. This
left you so far behind on your quotas that you had no hope of catching up, so
you stopped trying. You are not the only worker behind on your quotas, you
know some who are even further behind, so you don’t really understand why you
are here.

To be honest, you’ve never taken much interest in politics. It came as a
surprise to you to learn (from your mentor and fellow Triumph) that different
Cantons have different means of selecting their Triumphs and some even regard
it as a privilege rather than a punishment. There is a whole world outside
Canton 5 that you never even got to know about. You are amazed by what you see
around you but apprehensive about what the actual Games will bring.

---

## <a name="falc_smith"></a>{{< icon "star" >}} Triumph Falc Smith

*Rebel without a clue*

### What you hope for

To get a favour from Triumvir Smith that enables you to win the Games. And
maybe to contact some rebels as well

### How you got here

You were born and raised in Canton 5 and, like many of your peers, you believe
the entire system of the Imperium to be inherently unfair. Not every citizen
of every Canton has to work in the factories till they drop and could be sent
off to the Games for a failed quota. You know that Castor Smith rose from
humble origins in your home Canton to be one of the three highest in the
Imperium and you guess he did this by foul means rather than fair ones. From
talk in the taverns of your Canton you are aware that, before he left for the
Eternal City, he had a bad reputation. Still, if the Triumvir has any fidelity
to his original Canton you might be able to get a favour from them. A favour
that would allow you to survive.

You have heard rumours about some sort of rebel movement, though it tends to
stay deep underground. It was in the hope of meeting up with the rebels and
helping their cause that you deliberately fell behind on your quotas. Perhaps
there will be rebels you can contact here in the Eternal City. Perhaps they
will even help you to survive the Games. But best not to talk about that with
anyone you don’t trust.

---

## <a name="brook_smith"></a>{{< icon "medal" >}} Mentor Brook Smith

*Hard bitten former victor. Knows much, speaks little*

### What you hope for

To train and discipline your Triumphs

### How you got here

Your Canton does not have a bad record in the Games. OK, you’re not consistent
winners like Jupiter’s Canton or the soldiers from Mars, but Vulcan produces
hardy souls. The Smiths can be rebellious, but resentment for the system can
be a great motivator in the Arena. As long as that resentment doesn’t involve
trying to get people to rise up against the Imperium. That kind of attitude
gets people killed, in or out of the Games. Your Triumph won last year. You’ve
heard rumours that they won via bribery, but bribery is part of the Games and
the gamekeeper who took the bribe is gone now — the penalty for taking bribes
is death. You didn’t have anything to do with it — you’re too fond of your own
skin to get into that — and you think it’s safer if you never find out who was
responsible. You’ve heard rumours it was someone very high up, but it is
better to keep your mouth shut than indulge in the kind of talk that would get
you branded a rebel.

You won your own Games by sheer bloody-minded persistence. Working in the
factories made you strong and nimble. One of the Triumphs from Canton 8 was
favourite to win, but they pissed off two of the Gamekeepers with sheer
arrogance, so they never got the weapons and conditions that suited them. Your
mentor curried favour with good sponsors. One of the Triumphs from Canton 6
was exceptional that year. You thought they might beat you with their
improvised technology and expertise at laying traps, but you killed them when
there were only three of you left — in the final half hour of the Games. It
was a close-run thing and it still gives you nightmares. It was your strength
that enabled you to wrest the advanced weapon from their grasp but sheer luck
that you managed to turn it upon the unfortunate Wright.

---

## <a name="castor_smith"></a>{{< icon "landmark" >}} Triumvir Castor Smith

*Rags to riches and great power*

### What you hope for

To establish yourself as Emperor and sole ruler of the Imperium

### How you got here

You are one of the Triumvirate and you worked your ass off to achieve your
position. Born in grinding poverty in Canton 5, your father lost his job in
the local factory due to a chronic, alcohol-related inability to fulfil his
quotas. He beat your mother. You were determined to rise above your humble
origins. You worked hard. You achieved promotion by driving the workforce to
their limits and beyond. Production soared when you were in charge. You
attracted the attention of one of the Fortunate and were put in charge of a
factory. There you learned new skills — how to bribe and threaten your way to
further favors. You formed an organization, some, unkindly, would call it
criminal but the only thing that differentiated you from the corporations
heirs was that you built your empire yourself and didn’t kowtow to anyone.

Eventually you blackmailed the fortunate one to have you invited to the
Eternal City. There, through a web of connections you bribed, threatened, and
blackmailed your way onto the triumvirate. Something you will not give up
under any circumstances. You know all about grinding poverty and how to
control the grindingly poor. You ensure that they stay in line and, if anyone
gets out of line, you cut them down as publicly as possible so they serve as
an example to their peers.

You are not convinced electing Triumvirs is a good thing. You would much
prefer it if your descendants followed you into your position. You are not
convinced that Caroly Wendlesmith, your only child, is up to the job. Maybe
you should remarry and produce more children?

Annoyingly you have been assigned a new bodyguard — Sky Bright. You have no
idea who put someone not screened by your own people in a position so close to
you, but you are determined to find out.

You have dirt on many powerful people and you’re not afraid to use it.
Increasingly, though, you worry they might be in a position to blackmail you.

---

## <a name="indigo_smith"></a>{{< icon "landmark" >}} Indigo Smith

*Childhood friend and second in command*

### What you hope for

A violent and bloody show

### How you got here

You came to the Eternal City from Canton 5 with Triumvir Smith. The two of you
grew up together and have always been close. You know precisely how Castor got
their position — bribery, corruption and occasional violence. You remain their
main connection with the criminal underground. You do the dirty work, Castor
keeps their hands clean and you are well rewarded. You wield a great deal of
power in the Imperium, though you don’t get a lot of recognition. Castor got
you a job on the Board of the Maddox corporation and that provides you with
cover for the work you actually do. Which mostly involves ensuring everyone
stays in line.

It’s been a long time since you’ve beaten or murdered anyone yourself. You
have an army of thugs happy to perform such tasks on your behalf and an army
of thieves and drug dealers to provide the necessary finances. It’s a good
life but sometimes you wonder whether Castor appreciates you enough. You
could, after all, sell them out quite easily — if the price was right.

You’re quite unhappy that Castor wants to change the system so that their
heirs will follow them into that role. It doesn’t seem right to you,
especially as their child is a dead loss, in your opinion. At the same time,
if Caroly Wendlesmith is to be Triumvir, or Emperor or whatever, maybe one of
yours should become their chosen life partner. That would be a great way to
keep them in line! You have plenty of children, Castor only has one.

You have always enjoyed the Games. You enjoy the spectacle. The bloodier and
more violent things get, the more you like them. You don’t really have any
great need to support your home Canton, but you enjoy betting and are keen for
any investments you make in that direction to be successful.

---

# {{< icon "atom" >}} Minerva’s Children

## <a name="ban_wright"></a>{{< icon "star" >}} Triumph Ban Wright

*The test pilot*

### What you hope for

To prove the efficacy of your new armour

### How you got here

You were born and raised in Canton 6. You were working on a team whose job it
was to perfect a new kind of flexible armour — a commission from the Maddox
Corporation. The team was out celebrating their success one night quite
recently when it occurred to someone (no one remembers precisely whose idea it
was) that the Triumphal Games would be the best place to test out just how
well this stuff actually works in combat conditions. You volunteered. Maybe
you were a bit drunk, but you can’t honestly say you regret it. You have every
faith in the material you helped develop and are proud to be the one to try it
out.

Your family are angry with you. They think you’ve chosen far too risky a
course, but you are confident this material will win you the Games and that
you will live out the rest of your life in luxury. Your lab team back in
Canton 6 are cheering you on and you expect Maddox to back you. Over the last
couple of days, though, you’ve run into a couple of snags. Your fellow
Triumph, thinks you should ‘share’ the armour. You regret that you ever shared
your ‘secret’ with them. And your mentor is uncertain whether wearing your
armour in the actual Games is permissible. The Gamekeepers, or maybe the
Triumvirs may need some persuading. You don’t see this as a massive problem.
Goura Wright, the Gamekeeper will doubtless take your side and Maddox will
surely help. And why shouldn’t you wear what you want to wear? Everyone else
round here does.

---

## <a name="jules_wright"></a>{{< icon "star" >}} Triumph Jules Wright

*Resentful person*

### What you hope for

To get out of this alive

### How you got here

You were born and raised in Canton 6 and you are seriously angry that they
chose you as a Triumph. You did your best to appeal the decision, but no one
was listening. To hear them talk you would have thought you’d deliberately
sabotaged the genetic splicing experiment. It was an accident. You are not
normally clumsy, but your mind was on your private life and not your work.
Your lab coat caught on the corner of the table when you were opening the door
of the cage to feed the experimental animals and one of them got out. And the
one that got out turned out to be pregnant. Now the damned things are breeding
all over the facility and everyone is blaming you (not whoever it was that
allowed the animal to get pregnant in the first place).

Your supervisor recommended you to the committee as a Triumph, she called you
‘that clumsy oaf’ which was not a nice thing to say. You honestly do not
believe you were at fault and death in the Games is a high price to pay for a
momentary lapse in attention. That said, you will do whatever you can to
survive. You’re not exceptionally fit or athletic, but you know how to use
your brains. Also, your fellow Triumph has some kind of new armour they’re
testing. Maybe you could have some too?

---

## <a name="tobin_wright"></a>{{< icon "medal" >}} Mentor Tobin Wright

*Brains over brawn, though a little athleticism helps*

### What you hope for

To train a Victor

### How you got here

Minerva’s Canton has won the Games four times and every time the Victor
survived by inventiveness and cunning. The Wrights produce brain rather than
brawn though, of course, some athleticism is a great advantage. The four
former Victors generally come to a consensus about who is to act as Mentor in
any given year though Hamish is getting rather too old and Sully doesn’t
really have the experience yet. In effect, you and Marion tend to take turns.

You have two very different Triumphs this year. One volunteered because they
want to test a new piece of equipment. They’re enthusiastic about it so you
hope you can persuade the Gamekeepers to allow that armour into the Games.
Either that or work out how to disguise it as part of a costume. It doesn’t
look a lot different to some kind of high-tech fashion fabric so you’re not
anticipating a huge amount of difficulty. You need to persuade Ban that no
piece of equipment is foolproof and no Victor ever got to survive just because
they had a particular weapon or item. There is more to the Games than that.
Jules is being punished for a piece of clumsiness that wrecked an experiment.
They seem to be seriously resentful about their selection. Maybe that can be
turned around — anyone is potential Victor material.

You think you can work with Kelly Weaver on the high-tech material. Kelly
understands that kind of thing and can help you and your Triumph to make a
fashion feature of the armour. Kelly has a great relationship with the media
which is helpful. Goura Wright (Gamekeeper) might also be able to assist and
still has ties to your home Canton. And, of course, you’ll be working with the
other mentors to ensure both your Triumphs are on strong teams.

---

## <a name="goura_wright"></a>{{< icon "landmark" >}} Gamekeeper Goura Wright

*Setter of tricks and traps*

### What you hope for

Revenge on Brook Smith who killed your lover

### How you got here

You were born and brought up in Minerva’s Canton. Your inventiveness got you
noticed and a few years ago, you received an invitation to the Eternal City to
help devise tricks and traps for the Triumphs. You’re good at this work and
you enjoy it. You work closely with the media and have a good feel for the
sorts of challenges the audience will enjoy. It is, after all, important not
to kill all the Triumphs off, and not too many of them in the first half hour.
Stafford Piper, who is the official liaison between your team and the media,
understands this well and the two of you work well together.

Back when you were living in Canton 6 you formed a close relationship with Lee
Wright. Lee was brawn to your brain. The committee chose Lee to serve as
Triumph. You assisted them with their training, and, to this day, you are
convinced that if all had been run fairly, they would have won. But no, they
died in the final half hour at the hands of Brook Smith, the current mentor for
Canton 5. You never really got over it and you are looking for revenge. If you
get your way, the Triumphs for Vulcan’s Canton will suffer. But you will have
to be sneaky about it. Not only will your fellow Gamekeepers be on the lookout
for any unfairness, but Triumvir Castor Smith is known to favour their home
Canton… Obviously you retain a fondness for Minerva’s Canton but you can’t
afford to let that get in the way with your professional detachment, or your
revenge.

---

## <a name="munroe_wright"></a>{{< icon "landmark" >}} Munroe Wright

*Child of rebels, trying to make good*

### What you hope for

To prove your loyalty to Baradras

### How you got here

Your family comes from Minerva’s Canton. You, however, were born and brought
up in the Eternal City. Your mother was headhunted by Baradras Pharmaceuticals
and ended up as one of their top scientists. She’s back in Minerva’s Canton
now, by her own choice. Your father was banished back there after he was
caught criticizing one of the previous triumvirs. She decided to follow him.
You did not. You’re doing too well in your corporate career and you have never
felt much of a tie to your origins. You knew that your father had connections
with dissenting movements within the Eternal City but you neither denounced
him nor felt any need to find out more about his political shenanigans. You do
worry, though, that some rebels might recognise you and mistakenly believe you
share your father’s sympathies.

You were subjected to a number of interviews in which you had to prove your
loyalty to Baradras Pharmaceuticals and you count yourself fortunate that you
still work for them, are still in the Eternal City and have been given the
responsibility of representing your Corporation at the Triumphal Games. You
are in a position to arrange drops of medical supplies to any Triumphs you
chose. It really doesn’t matter to Baradras whether they end up winning or
not, it’s the curative effects of the product that they wish to publicise.
It’s quite exciting really, because you find yourself in the position of being
able to decide who will live and who will die.

One complication is that Downland Pharmaceuticals, a rival corporation, seem
to have a large presence here. You know they use underhand methods and you
need to take care of your own safety.

---

# {{< icon "coins" >}} Mercury’s Children

## <a name="swift_silver"></a>{{< icon "star" >}} Triumph Swift Silver

*Embezzler and sneak thief*

### What you hope for

Enhance the reputation of the Moneylenders Guild. Maybe make a bit of cash on
the side.

### How you got here

You were born and raised in Canton 7. There you worked as an enforcer for the
Moneylenders Guild. Not a job that makes you popular, to be honest, but you
quite enjoyed it, managed to line your pockets a little on the side. Which,
you guess, is why you ended up as a Triumph. The guild doesn’t appreciate
being short changed. You’re nervous about the Games, naturally, you’re no
great athlete, but you are wily and lithe and, truth to tell (though you don’t
admit it) you’re good at stealing and concealing things. You know how to
distract your mark so that they don’t notice your sleight of hand. You think
this could come in useful in the Games.

You do retain fidelity to your Canton and your Guild. You want to make them
proud of you. Putting on a good show, whether you survive or not, will do a
lot to enhance the reputation of the Guild and you might even manage to get
the Triumvirate to recognise the Money Lenders Guild, something they have, to
date, been reluctant to do. So, whatever, you’re determined to make the best
of a bad job. You’re enjoying your time in the Eternal City. You’ve managed to
pick a few pockets and… well, you might as well die rich as poor.

---

## <a name="blair_silver"></a>{{< icon "star" >}} Triumph Blair Silver

*Amateur athlete and team player*

### What you hope for

To survive as part of a strong team

### How you got here

It’s not very often that the Transport Guild needs to put forward a Triumph.
This year, however, there have been a number of snags and delays — a
combination of bad weather and rebel actions. The Guild-Masters decided that
your Guild had not performed as well as it should and your Guildmaster put you
forward. They put you forward because as well as being fast on your feet and
intelligent, you have a reputation as an amateur athlete. You won the
triathlon in your Canton three years running and you expect to do well at the
Games.

Apart from your own acknowledged talent, the whole guild is rooting for you
and you are confident they will send you regular drops of supplies and weapons
during the course of the Games. Winning is, of course, never guaranteed. So,
whilst it’s difficult to avoid the parties and celebrations that surround the
Games, you’re using as much time as you can to assess the strengths and
weaknesses of the opposition. The Triumphs from Cantons 1 and 8 are
professional in their approach, you’ve studied their form. Perhaps you could
form an alliance with them? It would be a mistake, though, to underestimate
the rest of the field. Every Canton has produced at least one Victor.

---

## <a name="silence_silver"></a>{{< icon "medal" >}} Mentor Silence Silver

*Ambitious wheeler dealer*

### What you hope for

A Victor from your canton.

### How you got here

It irks you that Mercury has only ever had two Victors. Your fellow Victor,
Seamus, was one of the earliest and now insists he has retired, leaving you to
mentor those who follow. But it’s not the work that bothers you. You believe
that the Silvers could do a lot better. One problem is that they keep sending
you poor material to work with. Though that should not make so much difference
— it’s not so much what they can do, as their attitude. Speed and strength
alone do not win the Games — cunning and trickery are just as important, and
Mercury should excel at both.

You won your crown by convincing teams led by the favourites (Mars and
Jupiter) to face off against each other in the last hour. Then you waited,
making yourself ‘useful’ by tending to the wounded till the survivors killed
each other off. Your medical ministrations made you popular with the audience
who still don’t know what  you were actually doing. There was a very touching
scene at the end when you treated the wound of the last man standing and he
dropped dead at your feet.

You have advised many corporate heads and even Triumvirs on certain covert
financial transactions. As such you have blackmail material on some powerful
figures. As you always make a bit on the side, you have considerable financial
resources.

You also know **Milan Silver**. They are from your Canton so it’s only natural
that you hang out together. You know that they are ‘on the make’ and insist on
a sweetener before anyone gets to see their boss. But that’s fine. That, after
all, is how business is done, how profits are made.

---

## <a name="milan_silver"></a>{{< icon "landmark" >}} Milan Silver

*Ambitious Personal Assistant to Triumvir Amory Gold*

### What you hope for

Permanent residence in the Eternal City, power and wealth beyond the dreams of
avarice

### How you got here

You were born and brought up in Canton 7. Your acumen was recognised, and you
were put forward as a possible candidate to serve in the Eternal City.
Triumvir Amory Gold interviewed you and took a liking to you. More fool them.
Triumvir Gold is a fool. Hopelessly privileged, they don’t realise how
everyone dances around them catering to their every whim. They are also a
hopeless idealist and naïve enough to entrust you with their entire schedule.
So, of course, you’ve made a nice profit for yourself. No one gets to see the
Triumvir without lining your pocket or doing you a favour.

You believe Triumvir Smith to be corrupt. It is beyond you to understand how
anyone could have failed to notice. Not just corrupt, you believe they are
trying to make themselves Emperor, so that they can occupy the position for
life and have their child follow them. You are torn between blackmailing them
and trying to get close to their child, and work to become the life-partner of
a future Emperor. Triumvir Smith has a new PA, September Fletcher, who doesn’t
seem to know what they are doing. You could mentor them, as they seem to want,
or you could undermine them, which might be more fun.

You are close friends with **Silence Silver**. You know their secret. Whilst you
don’t mind making a bit of cash on the side, you’re reluctant to betray such a
dear friend.

---

## <a name="ellis_silver"></a>{{< icon "landmark" >}} Ellis Silver

*Competent and ruthless representative of a pharmaceutical corporation*

### What you hope for

Promotion, probably involving undermining your rivals

### How you got here

You came to the Eternal City on an invite from the Downwater Pharma
corporation due to your ability to play and manipulate the markets. Prior to
that you’d been a member of the Speculators Guild. You worked hard and your
talent and education bought you promotion, promotion over the head of Lennox
Downwater who clearly resents your position and will do what they can to
undermine you.

You are attending  the Games to advise Downwater on which Triumph they should
sponsor. That’s  difficult for you as you would dearly love to see someone
from your own Canton win. You’ve researched their two candidates. You do not
intend to support the one from the Money Lenders. They are just bad news, but
the Triumph from the Transport Guild looks promising.

It would be possible for you to supply drugs to damage a Triumph as well as to
enhance their performance.

You will be betting on these Games as well. For personal profit. Your rival,
Lennox Downwater is keeping a book and the more they lose, the less likely
Downwater is to promote them over your head.

Hamilton Maddox is testing out a new drug for Downwater. You need to keep an
eye on how that is going, though the close relationship between Downwater and
the Maddox heir should remain secret.

Baradras corporation also has a representative here. They’re a serious rival
to Downwater in the Pharmaceuticals market, you will try your best to
undermine them. Showing that they were trying to pervert the integrity of the
Games (maybe by nobbling a Triumph) would be a major achievement for you.

---

# {{< icon "shield-alt" >}} Mars’ Children

## <a name="red_ward"></a>{{< icon "star" >}} Triumph Red Ward

*Sergeant major, dishonourably discharged for abusing recruits*

### What you hope for

Trial by combat

### How you got here

It’s been just less than a year since your dishonourable discharge from your
post as an NCO in Canton 8. The charge that you abused recruits was manifestly
false. Your court-martial was a farce. You were tough, yes. You had to be. You
had to harden up those soft recruits if they were to stand a chance of
survival on a real field of battle. That’s the problem with the brass in
Canton 8. They have forgotten the army exists for war, not for smart
manoeuvres on the parade ground.

Since your discharge you have struggled with everything. You won’t admit
weakness, but the plain fact is that your personality and training have ill
fitted you for civilian life. Becoming a Triumph was the only course left open
to you and you are happy you landed the mission. You don’t care about the
honour of your Canton. For you this is a personal trial by combat. Either you
win, in which case your troubles will be over, or you will lose. If you lose
it proves you were not worthy to survive.

---

## <a name="ripley_ward"></a>{{< icon "star" >}} Triumph Ripley Ward

*The professional soldier*

### What you hope for

Survival or martyrdom to bring wealth and honour to your family

### How you got here

You were born and raised in Canton 8 so, naturally, you are a soldier. It is
the only life you have ever known. You are proud of your Canton and proud of
your own military background. Your family is not one of the well-renowned, so
you have found it hard to get promotion, although you and your superiors are
confident of your ability. You guess that is why they offered you the chance
of becoming a Triumph. You thought long and hard before you accepted. At the
end of the Games there will be one Victor and 23 dead. You’re a soldier
though, death is something you know you might need to face at any time. And,
whatever the outcome, you know your loved ones will be honoured and cared for
better than you could manage yourself. Even if you got the promotion you know
you deserve.

Your fellow Triumph is known to you, at least by reputation. He was
dishonourably discharged from service about a year ago. You heard it was for
mistreating recruits. Well, NCOs can be harsh. They need to be harsh in order
to harden the recruits but sometimes… Well, sometimes a Sergeant Major takes
it too far. You’re not sure whether or not that is true in Red’s case. They do
seem rather overconfident of their own ability and your military training
taught you that overconfidence is a liability in a combat situation. Alertness
and caution are what keeps a soldier alive. And teamwork, even if you end up
having to sacrifice your own team. You know you will find this hard.

---

## <a name="strega_ward"></a>{{< icon "medal" >}} Mentor Strega Ward

*If I wasn’t a mentor, no one would want to kill me.*

### What you hope for

To know the enemy who is trying to kill you. To avoid the shame if you fail to produce a Victor

### How you got here

It’s tough mentoring triumphs from Mars’ Canton. Tough for a number of
reasons. For a start there are your fellow Victors. The Media present the
rivalry between you as ‘friendly’ although in reality it is anything but.
Sedro, who was mentoring up to three years ago, is dead. Her murder remains
unsolved, but you are fully aware that it was organized by one of the Victors.
You’ll never reveal it, of course, the squaddies take care of their own.
You’re not sure which Victor it was anyway. The perpetrator may get jumped on
a dark street corner, or maybe not. One thing is for sure, they’re not going
to take your place as Mentor. You do lie awake some nights, wondering if you
will be next to die.

Another factor that makes your task harder than it might be is the common
conviction that one of your Triumphs will survive. Mars has a good record at
the Games, and it will not go down well in the Canton if you fail to uphold
it. It won’t go down well with Maddox corporation either — they’re naturally
inclined to support military Triumphs, but you need to work closely with them
to ensure your mentees get the best of the best. You know Hamilton Maddox is a
dead loss and has problems with his family. Their official rep, Paris Ward, is
a better prospect. Paris was very friendly with Sedro and, no doubt, wants to
solve the murder. Which gives you a dilemma as, on the one hand, you would
like some kind of protection from assassination and, on the other hand,
squaddies should be sticking together… In any case, forming a good team with
your mentees at the head has to be your main concern this weekend.

You have limited material to work with. Red is a lout — dismissed from their
post for bullying recruits and Ripley, though likeable, is under confident
though probably not totally inept. Some years are easy. This year you have
hard work ahead of you if you’re not to let the side down.

---

## <a name="paris_ward"></a>{{< icon "landmark" >}} Paris Ward

*Research and Development coordinator for Maddox Corporation*

### What you hope for

You have a lot of delicate work here. You hope to perform it well.

### How you got here

Back when you were living in Canton 8, you had a successful military career.
More of a thinker than a fighter, your specialism was the development (in
conjunction with Canton 6) and procurement (in conjunction with Cantons 5 and
7) of military equipment. Maddox Corporation, who specialise in military
hardware invited you to work in the Eternal City, doing much the same work as
you were doing back home. You are a valuable asset. Not only do you have a
good understanding of military needs, but you are an effective negotiator and
tolerate long meetings better than most of your Canton compatriots. You have
enjoyed several promotions. You brought members of your family to the city to
be closer to you and you fully expect to remain here for the rest of your
life, unless, of course, you mess up. These days, you reckon, you think pretty
much like a native of the Eternal City, though, of course, you still have
loyalty to Mars.

You are here as a corporation representative, in a position to provide drops
of advanced hardware to worthy Triumphs. You worked closely with Sedro, the
recently murdered Mentor for Canton 8. You’d quite like to know what happened
to her as she was a friend as well as an associate. You have no special
relationship with Strega Ward, the current mentor but you are vaguely aware
that not all the previous Victors from Canton 8 get on with them. In any case,
you are here to further the interests of Maddox corporation and you can’t
afford to play favourites with your own former Canton. You are aware that one
of the Triumphs from Canton 6 is ‘test-driving’ a new form of armour and that
interests you greatly. Your instructions are to ensure that the testing is
thorough and to commission the equipment if it works.

Maddox Corporation is aware that Hamilton is working with Downwater Pharma.
You need to find out the nature of that connection and generally keep an eye
on the wayward Maddox offspring.

---

# {{< icon "sun" >}} Apollo’s Children

## <a name="jan_bright"></a>{{< icon "star" >}} Triumph Jan Bright

*A lover not a fighter.*

### What you hope for

To have a good time before you die — unless you can find some way to survive

### How you got here

You were born and raised in Canton 9. Your mother was a supervisor responsible
for the output of one of the solar plants. Your father was well known for his
musical talent. Something you inherited. Your father helped out around the
plant and around the house, but he always preferred playing his guitar and
singing to working hard. You inherited that too. You have to work of course,
you need to contribute to the household income, and you earned your money
serving drinks in the local bar where your father plays. Both of you are
popular locally and you have never been short of a romantic partner or two.

All that is in the past. The oracle chose you. You were raised to believe in
Apollo, and you know the oracle does not make errors. You were chosen for a
reason. Maybe you are a sinner. Maybe one of your discarded lovers prayed for
revenge. Who knows? It doesn’t matter now. You’re a lover not a fighter and
you don’t think you stand a chance of survival in the Games. So, you might as
well have a good time whilst you still can. Everyone wants a brief fling with
a Triumph, don’t they? There’s food and drink, wine and song a plenty here
and, it is rumoured, some more exotic pleasures available to anyone who knows
where to look. Anyway, if you can make the other Triumphs like you enough,
they might not want to kill you. The whole thing is distasteful — you’d rather
just play guitar.

---

## <a name="cal_bright"></a>{{< icon "star" >}} Triumph Cal Bright

*A focussed and determined worker*

### What you hope for

To survive, though you know it will take hard work and the blessing of Apollo

### How you got here

You worked in a power plant in Canton 9. It was a life. Not a particularly
good one but not a bad one either. You’ve heard the rebels preaching and read
one or two of their tracts. There were a lot of those going around the plant
you worked in. You understand they have a point. Those in the Eternal City
live in luxury whilst those in the Cantons labour to produce the goods that
enable them to live in luxury. Strictly speaking that is not fair. But, as you
understand it, it’s the way things are, the way they have always been. Sky
Bright was your supervisor at one time. They were very keen on those rebel
tracts and their rebellious thoughts and actions got them carted off to the
prisons of Pluto’s Canton. Or so you thought. You can’t help noticing that
Castor Smith’s bodyguard looks very much like your old supervisor. Could they
be the same person?

All that, however, is no more than a distraction. If you don’t concentrate
really hard on what your mentor tells you, if you don’t make a good enough
impression on the sponsors and Gamekeepers, you are going to die. Maybe you
will die anyway. But, unlike your fellow Triumph who seems keener on enjoying
the delights of the eternal city than they are on harsh training, that doesn’t
mean that you’re not going to try your hardest to survive. That way you can
join your mentor and the other Victor from your Canton in the Eternal City.

---

## <a name="rain_bright"></a>{{< icon "medal" >}} Mentor Rain Bright

*Dying from the desperate measures they took to become Victor*

### What you hope for

To get another Victor for your canton before you die

### How you got here

Maybe it’s blasphemous, but you can’t help wondering why the Oracle doesn’t
choose stronger candidates for their Triumphs. There are only two Victors here
in the Eternal city, you and Cerdwyn. Both of you won by sneaky means. You
were a chef before the Oracle called you and volunteered to cook for the
Triumphs. Late on the last day you poisoned the food with cyanide, to which
you had built up an immunity. It’s this thing called the mithridatic process.
Sadly, it doesn’t work as well as you believed it would and you are now
suffering the effects of having ingested a whole load of cyanide in your
youth. You are in constant pain, and dependent on a cocktail of expensive
drugs to keep on your feet. Hamilton Maddox provides the drugs but the price
keeps going up… You don’t think you will last much longer so you are quite
glad that Cerdwyn is around to take over from you.

You’d like to get another Victor for the Canton before you die. One of this
year’s seems devoted to nothing other than eating, drinking and being merry
and no doubt tomorrow they will die, though their sunny nature could make them
friends amongst the other Triumphs. The other is ready to train and to learn
but is not making themselves popular. Both of them are strong-minded and you
need to take care if you are to lead them in the right direction. Teamwork,
you feel, could be a deciding factor here.

---

## <a name="sigil_bright"></a>{{< icon "landmark" >}} Sigil Bright

*Voice of the third Triumvir*

### What you hope for

To defend your boss and, thereby, your own position of power

### How you got here

You are personal assistant to the Triumvir Hedony Melody. You speak for them
when they are not around. You speak with their voice and, therefore, people
(including the other two Triumvirs) listen to you. You cannot, however,
exercise your boss’ vote. There are limits to your power. Triumvir Melody is
not here, they have not been seen for several weeks and their public
appearances had been sporadic for some time before that. There is a great deal
of speculation around this and the reasons for it. The media have not got hold
of any potential scandal yet. They have the sense to be wary of a public
figure as important as a Triumvir. But you can feel them circling like a pack
of dogs around a bone.

You are personally faithful to Hedony. They have always treated you well. It
is very much in your interest to defend their reputation. You, however, are
very much aware that they are ‘losing it’. Hedony is no longer fit for office.
You are their voice and you mean to use it well. You also need to deflect any
questioning of Hedony’s competence. If they lose their job, so do you. You
enjoy the considerable power you wield and do not want to lose it. Triumvir
Gold is not a threat, you couldn’t say the same about Triumvir Smith. You have
to watch your step around Castor. You believe Castor wants to get rid of both
the other Triumvirs so they can rule alone.

Although you have come to think of yourself almost as a citizen of the Eternal
City, you have some fidelity to your old Canton and would love to see one of
their Triumphs win these Games. Their mentor, Rain, seems a bit… unwell.
Perhaps you should look into this. And you certainly want to talk to the
Triumphs and discover any news they might have of your old home.

---

## <a name="sky_bright"></a>{{< icon "landmark" >}} Sky Bright

*Newly appointed bodyguard to Triumvir Castor Smith*

### What you hope for

To start an effective rebel movement

### How you got here

Originally from Canton 9 you are currently under deep cover. You have long
been convinced that the entire system of the Imperium is corrupt and rotten to
the core. The few in the Eternal City oppress those in the Cantons without
whom they could not survive. You worked as a technician in a power plant where
you diverted energy to the people for free, rather than having it go through
the profiteers in charge of distribution. Your position as a supervisor
helped. It would have gone a lot better if you hadn’t decided to preach your
discontent to your colleagues. Marked down as a dangerous rebel, the guards
watched you carefully. You were careful not to let them get evidence against
you, so they framed you for a minor misdemeanour and put you on a train bound
for the prisons in Canton 4.

With the aid of some friends you escaped by leaping from the prison train. You
met up with a small group of rebels who are trying to get organised. They have
good contacts and were able to get you a false identity. Through conversations
with them, you have learned that Triumvir Smith is trying to bring down the
system and make themself Emperor. Your comrades in the movement got you a job
as Smith’s bodyguard and you are watching Smith closely for evidence of
criminality. It would be pointless to report this to the authorities. Triumvir
Smith is the authority but surely someone in the media could make constructive
use of the information?

---

# {{< icon "carrot" >}} Ceres’ Children

## <a name="arles_cropper"></a>{{< icon "star" >}} Triumph Arles Cropper

*Sacrificing yourself so your family will survive*

### What you hope for

Your family’s survival

### How you got here

You followed the fine tradition of your Canton by volunteering for the Games.
You do not think you are likely to survive. Only one Triumph from your Canton
ever became a Victor and Barley Cropper is  your mentor. You will, of course,
do the best you can. You owe that to your friends and family back home. And
your family are the very reason you are here.

The past several years bought poor harvests and your family — your entire
village — are utterly dependent on the land. You have seen infants die from
malnutrition, kids with swollen bellies, mothers getting thinner and thinner
as they struggle to feed their newborns. Your own family are no exception to
this. Your Canton has a tradition of rallying round villages that provide a
Triumph. The aid started to arrive at the village hall before you left. The
rich corporations who buy your crops sent enough bags of grain and flour to
alleviate the famine. If, by some miracle, you survive, you will be able to
celebrate with your family and community. If you don’t survive… Well, you have
the satisfaction of knowing that your family will live on and will honour you
in their memories.

One thing that bothers you is this: Cambourne fast foods sent famine relief to
the village after you volunteered. But lots of people had died by then. Why
couldn’t they do that before? Is it right that they stand back and let those
who provide their wealth die? Is it just because their lives are so distant
from the realities that surround your family? Before you die, is there
something you can do to improve things? Maybe you could have a word with the
Cambourne rep about it, assuming they have one here, because you think that
doing some humanitarian work could be good publicity for them.

---

## <a name="bel_cropper"></a>{{< icon "star" >}} Triumph Bel Cropper

*Volunteered recklessly when rejected by their beloved*

### What you hope for

You don’t really know anymore

### How you got here

You were born and raised in Canton 10 where your family own a flour mill. It’s
a profitable business and, despite the famines that plague your Canton, your
family always has enough to eat and sometimes has enough to share with the
wider community. Your friends, for the most part, consider you fortunate. So
why did you volunteer for the Games? It was done on impulse and you kind of
regret it. Thing is, you are madly in love with Demi from the next village
and, about a week before you volunteered, they rejected you. Definitively.
They are going to marry in a fortnight and you just can’t bear to think about
it. You thought about ending your own life so, when they came to your village,
asking for volunteers, it occurred to you that the Games would be the best way
to do it. It should have made your family proud of you. Well, it hasn’t, they
called you a bloody idiot. If you’d just quietly killed yourself, they might
have thought the same, but you wouldn’t have had to listen to them.

Maybe it was stupid to volunteer. You are certainly starting to have your
doubts. But it’s not something you can get out of now. Unless, of course, you
end up as the Victor. Fat chance of that! You do know that your family flour
mill was ultimately owned by Cambourne Fast Foods. Perhaps their
representative here will be willing to help you?

---

## <a name="barley_cropper"></a>{{< icon "medal" >}} Mentor Barley Cropper

*Jaded and lonely, but not entirely given up hope*

### What you hope for

A victor to keep you company

### How you got here

You are the only person from Canton 10 who has ever been a Victor and, since
your victory, you have had to serve as mentor every year, watching your
charges die in the arena. It’s depressing. At first you enjoyed life in the
Eternal City, basking in the attention you got as the first ever Victor from
your Canton. You took many lovers, you had many friends, you feasted. You
visited your family from time to time and were delighted to see them
comfortably settled. Your parents and siblings even got to visit you in the
Eternal City — in the beginning.

Time wore on and the pleasures started to bore you. Some go looking for
pleasures more extreme, you tried that, but it wasn’t really your scene. You
still miss your family, of course, but the pain has become less acute. The
only thing that breaks the boredom is the Games and… You’ve not managed to
coach a single Victor. You do your best to teach them the tricks that worked
for you. Make friends with the most promising looking contestants. Help them
(carefully) in the early stages. Hide well and don’t come out of your hidey
hole until all the rest are dead.

It doesn’t help that the Triumphs you get from the Canton tend to be poor
material. Neither of them has any confidence in their own ability. Maybe you
can help them to gain some self-respect? Maybe you can find them some
team-mates? For that you have to make them look like attractive propositions.

Outside the Games you are close to **Hemmy Cropper**, one of the Gamekeepers.
During the Games, though, you both understand that you have to keep a distance
from each other. It wouldn’t do for someone to get the idea that your friend
was unfairly biased towards their home Canton. You would like to get closer to
Arundel, the Cambourne heir. They remind you so much of how you were when you
first started to live in the Eternal City. And Cambourne, of course, are not
only in a position to help your mentees with their sponsorship but could do a
lot of good for your home village in Canton 10, from which you feel ever more
alienated and distant.

---

## <a name="hemmy_cropper"></a>{{< icon "landmark" >}} Gamekeeper Hemmy Cropper

*Tempted to be biased and, this year, bribed by a Triumph’s father*

### What you hope for

Not to get caught

### How you got here

You came to the Eternal City from Canton 10 to serve as a Gamekeeper. This you
have done faithfully for the past nine years. You are constantly tempted to
support the Triumphs from your own Canton but this year the volunteers, whilst
putting a brave face on things, do not seem to have what it takes to beat the
semi-professionals from Cantons 1 and 8. Both lack the killer instinct that
typifies a Victor. You are very close to **Barley Cropper**, who has to serve as
mentor. You worry about them as they have become jaded over time and are only
a shadow of their former self. During the Games you both understand that you
have to keep a distance from each other. It wouldn’t do for someone to get the
idea that you were biased towards your home Canton.

This year, to your shame, you have taken a bribe. The family of one of the
Triumphs from Canton 1 are desperate for their Triumph to survive. They want
you to organise some sort of escape and, if that proves impossible, to ensure
their offspring wins. The Triumph in question is well trained, they have the
killer instinct. It should not be too difficult to arrange. In fact, you might
not even have to do anything. If the Triumph in questions survives the Games,
you will receive wealth beyond your wildest dreams and a comfortable home in
Canton 1, should you not be able to remain in the Eternal City. If the Triumph
in question dies, you get nothing. Well, you get to keep your integrity whilst
gaining some powerful enemies amongst the administrators. The punishment for
taking a bribe is death. You’ve seen it happen.

---

# {{< icon "leaf" >}} Diana’s Children

## <a name="briar_fletcher"></a>{{< icon "star" >}} Triumph Briar Fletcher

*The great hunter, believes they can become the Victor — but has doubts*

### What you hope for

To become the Victor

### How you got here

You were born and raised in Canton 11. Diana’s Canton honed you well and you
are known as one of the best of her hunters. Up until this year, you’d been
one of the trackers who helped to select the Triumphs. You could have done the
same this year, but decided you wanted to attend the Games. Your friends and
family think you’ve gone mad — maybe you took a knock to the head in the woods
or something. But you have thought this through carefully. The Canton does not
have a glowing reputation. Natives of the Dryad Canton don’t get rich. You
reasoned that, if you got yourself a place as a Triumph and win, you would be
able to get better treatment for the Dryads. Due to the selection method, your
Canton tends to send its worse (and even then, you’ve had three Victors). It’s
time to show the Eternal City what Diana can do when she sends her best!

You know **September Fletcher**, you were friends at school. You suspect they may
have had a crush on you. You can play on that… They’re close to a Triumvir and
the Triumvirs are all-powerful.

You intend to win. You’ve been training hard and you continue to train hard
with your mentor. You’re also enjoying the entertainment laid on for you, but
in moderation. You want to be in peak condition when the actual Games start.
Everything else is a distraction. There have been a couple of occasions,
mostly late at night, when you’ve had doubts. There is, after all, no way you
can guarantee that you will win these Games. Some of the other Triumphs look
extremely capable. But you push those doubts to the back of your mind, try to
distract yourself by thinking of all the times you ran wild in the woods,
overcoming every obstacle nature put in your path. You can survive this. You
know you can. They say that teamwork is important in the Games, but who can
you trust?

---

## <a name="jaz_fletcher"></a>{{< icon "star" >}} Triumph Jaz Fletcher

*The naïve idealist*

### What you hope for

To help bring about a more just society

### How you got here

Up till now, you lived all your life in Canton 11. You lived with your family
out in the woods, cutting wood and supplementing your inadequate income with
the fruits of your hunting. It’s a harsh life but most count it good enough.
You’re not sure you agree with them. You’ve seen things. You’ve seen things on
the television and when you went to the trading post to barter or deliver your
log quota. You’ve seen that not everyone lives as you do. You’ve tried to work
out why that should be — why the denizens of some Cantons have things that
those from other Cantons do not — and it all seems very unfair. Those people,
the merchants and transport guys from 7, the teachers from 1 and the
whatever-they-ares in the Eternal city. They have two arms, two legs and a
brain, just like you do. They eat and fuck and piss and shit. But they have
stuff and you don’t.

From tavern talk you learned that you are not the only person who feels that
way. You were up drinking late the night before the trials, drinking with some
guy from Canton 7, a couple of Elders from your own Canton and a train guard
from Canton 10. There is some kind of movement going on. Oh, it’s all very
secret and underground right now but there is work to be done. A lot of work
to be done if people are to be treated fairly instead according to the random
accident of which Canton they were born in. They got you to sign up.

The next day, you were hungover. You stumbled and the trackers caught you
first. You’re better now. Unsure whether you’re good enough to win the Games
but… Maybe there is something you can do here for the rebel cause?

---

## <a name="sam_fletcher"></a>{{< icon "medal" >}} Mentor Sam Fletcher

*Tortured by their memories of killing their lover to become victor*

### What you hope for

Peace of mind and another Victor for Diana

### How you got here

For a poor Canton, Diana does not do badly in the Games. She’s had three
Victors in the past and you believe she will have more in the future. Though
Victory in the Games must always come at a price. You discuss this with your
fellow Victors often, over a few glasses of wine late at night. Everyone
sacrificed something. You sacrificed the Triumph who had become your lover. By
fidelity to each other, and joining up with a strong alliance, you were the
last two left. Neither of you wanted to kill the other but… You had no choice.
When you are mentor you always warn your mentees not to form close
relationships. Death is easier and death in the Games is not a shameful
matter.

This week it is important not to brood too much. These new Triumphs are
depending on you. You need to show them how to win. Being Fletchers, they will
already be excellent at tracking and trapping. You can help them hone those
skills. You need to concentrate on that, not the terrible memories the Games
always evoke.

You worry about September Fletcher. They are from your Canton and you see them
getting kicked around and exploited by their boss. OK, the boss is a Triumvir,
a very important and powerful person, but there is no need to treat staff
badly. You also suspect that Milan Silver sees them as a rival and tries to
undermine them. Sadly, September does not seem interested in listening to your
advice.

You know you need to keep an eye on the Gamekeepers. They have a tendency to
take bribes (well, you can understand the temptation). You were hard put to it
not to cheer last year when the woman who had deprived your mentee of their
victory (not to mention their life) was executed.

---

## <a name="september_fletcher"></a>{{< icon "landmark" >}} September Fletcher

*PA to a Triumvir, newly promoted and bullied by their boss*

### What you hope for

To make your Canton proud and to renew your acquaintance with Triumph Briar
Fletcher

### How you got here

You came recently to the Eternal City from the forests of Canton 11. You’re
still a bit overawed by the luxuries of the Centre but determined to serve
well and be a credit to your Canton and your family. Your boss is… difficult.
Castor Smith is very demanding and not slow to criticize, although sometimes
you’re not sure what you’ve done wrong. Which, of course, is entirely your
fault. The Triumvir is far too important to be wrong about anything. They do
seem to have some quite unpleasant people around them, maybe you should
mention this to them? Or maybe not — it could be taken as implied criticism
and make them lose their temper.

You look up to Milan Silver, PA to Triumvir Gold. They have been in the job
for a long time and seem quite confident about everything it entails. You
would like to get closer to them and get some good advice.

Although you are proud and honoured to have a chance to serve the Imperium in
the Eternal City you miss the forests of Canton 11, as well as the friends and
family you left behind. You were at school with **Briar Fletcher** (maybe even
had a bit of a crush on them) and seeing them again is exciting for you — a
reminder of home. You know that Sam, the Mentor from your Canton looks out for
you, but you can get irritated when they are too free with their advice. You
need to find your own way and they should be mentoring the Triumphs, not you!

---

# {{< icon "drum" >}} Venus’ Children

## <a name="syd_piper"></a>{{< icon "star" >}} Triumph Syd Piper

*The self-absorbed musical prodigy*

### What you hope for

To find someone who appreciates your talent enough to ensure you survive

### How you got here

You were born and raised in Canton 12. You were a musical prodigy, your talent
realised and praised by everyone who heard you play. You grew up knowing that
you were better than the other kids, and they were always jealous of you. Part
of your success is natural talent, but you also work hard, practising
constantly with the encouragement of your parents and your teachers. They
protected you from the rough and tumble most of your peers enjoyed. You were
far too precious an asset to mingle with the hoi polloi.

You did not expect to end up as a Triumph. The committee did not encourage the
public to vote for you but… You don’t know why they did. Usually they vote for
whoever the committee recommends, or for someone who puts on a truly
despicable performance. You strongly suspect it was jealousy. Whatever, you
are here now. You have watched the Games every year, it is, after all,
compulsory to do so, but you never took much of an interest. The Games were
just a distraction from your music. You are aware that your mentor is the only
person from your Canton ever to have won the Games. You should respect them
for that, but it’s difficult. It’s not music.

---

## <a name="cory_piper"></a>{{< icon "star" >}} Triumph Cory Piper

*The Clown*

### What you hope for

To make people laugh. If they’re laughing hard enough, they might not kill
you.

### How you got here

You were born and raised in Canton 12. You were always good at telling jokes
and had launched into a career as a stand-up comic. That’s how you ended up in
the talent contest. Sure, you always knew there was a chance you’d end up at
the Games, but it’s good exposure. And you needed exposure if you were going
to get somewhere. You guess you didn’t really understand how unpredictable
your Canton is when they vote someone into the Games. Sometimes they will
choose the candidate they think is the most talented, so that the Cabaret will
look good and sometimes they choose someone they don’t want to see any more —
rather like getting booed offstage but considerably more permanent. You’re not
sure which applied in your case.

You are determined to do Venus proud in the Games. You know full well that the
Cabaret has only ever produced one winner. That’s your mentor, Gentry Piper,
and you will learn what you can from them. You’re rather fond of your own skin
and will survive if you can. You’re not expecting a lot of help from your
fellow Triumph — Syd seems snobbish and stand-offish, and you suspect they
will not survive very long. Whatever, if you die, you will go out with a bang.
You will keep the audience entertained with your clowning and some of the
acrobatic tricks you use as part of your routine may turn out to have survival
value.

---

## <a name="gentry_piper"></a>{{< icon "medal" >}} Mentor Gentry Piper

*The fake*

### What you hope for

To coach one of your Triumphs to become a Victor. To find someone with whom to
share the burden of your secret.

### How you got here

Not many people know this, but you have never taken part in the Games.
Probably it would be better if Venus could find someone else to coach her
Triumphs but, as there has never been a genuine Victor from your Canton, there
is little choice. Of course, not having ever been in the Games is your
terrible secret, known only to yourself, Charleston Piper and the Triumvirs.
The film crew and Gamekeeper who witnessed what really happened have all met
with untimely ends — horrible diseases or terrible accidents.

The year you supposedly won the Games, all the Triumphs ended up dead.
Charleston Piper put out a call to Venus for a body double. That was you. And
one of the presumed dead was miraculously alive.

Every year since then you’ve had to act as Mentor to two new Piper Triumphs.
You feel like a fake, but you haven’t dared admit to it as that would
inevitably lead to your death and you don’t want to die. It would be nice if,
just this once, you could persuade one of the Triumphs to survive. That way
you would have someone with whom to share the burden of Mentorship, even if
you didn’t share your secret.

---

## <a name="charleston_piper"></a>{{< icon "landmark" >}} Charleston Piper

*The established media star*

### What you hope for

To balance all the demands on your time and attention to gain the maximum benefit

### How you got here

Born and raised in Canton 12, you were destined to become a star. You’ve been
in the business since before you could walk and, through talent and sheer hard
work you are now the most popular presenter in the Imperium. You know
precisely how to please the public. Your interview technique is impeccable.
Your viewers will believe whatever you want them to believe and, as such, you
have a great deal of influence over the outcome of the Games. If you present a
Triumph in the best possible light, they will attract sponsors. If you make
them look a fool on air (and it’s easy enough to do) their sponsors and maybe
even their mentor will abandon them.

You are not above taking bribes, but you have a reputation to maintain so
anyone who wants you to favour a particular Triumph had better make it worth
your while. An insulting offer can be… counterproductive. Like any other media
personality, you are susceptible to flattery, but you’ve been in this game
long enough to know that not all flattery is genuine. You are sweet as can be
when you’re on air but you do not tolerate fools gladly and have a fine line
of sarcastic invective for incompetent film crews, your support staff and that
hopeless new young puppy who is supposed to be your back up. Jess Weaver —
from Canton 3, not the Carnival, how low can you get?

---

## <a name="pip_piper"></a>{{< icon "landmark" >}} Pip Piper

*Herder of kittens*

### What you hope for

To get everything and everyone into the right place at the right time

### How you got here

You have the unenviable job of being personal assistant to both the MCs for
this year’s Games. It’s what you were raised and educated in Canton 12 to do.
It would be easier if Charleston did not despise Jess so much. It would be
easier if Charleston was not so full of themselves, it would be easier if Jess
had a bit more experience, or confidence. As things stand, you often feel like
you are the one holding the whole show together. You are in charge of liaison
between the Triumphs, their mentors, and the media. This is non-trivial as
many of the Triumphs do not seem to understand what they need to do. Even
getting them into the right place at the right time is like herding kittens.

One minute you might be getting Charleston the precise delicacy or prop they
crave, the next you might be persuading a weeping Triumph to smile for the
cameras, or you might be pacifying a mentor who feels that their Triumph has
not got the publicity they deserve. It’s challenging work and hectic. At least
Jess does what they can to make your life easier. You would like to see them
do well and, if you get to take Charleston down a peg or two in the process
well… so be it. On top of that you have heard rumours that someone here has
some dirt on one of the Triumvirs. If that’s true, it would  certainly make a
good news story!

---

## <a name="stafford_piper"></a>{{< icon "landmark" >}} Gamekeeper Stafford Piper

*Liaison between the Gamekeepers and the Media.*

### What you hope for

To be bribed or, failing that flirtation and inebriation.

### How you got here

You were born and raised in Canton 12. Your role amongst the Gamekeepers is to
ensure that everything the team devises looks good on camera. You act as
liaison between your team and the media and you are appreciative of the help
you get from Goura Wright, another of the Gamekeepers who understands what the
media need. You’ve been doing this job for years and, frankly, it gets boring.
You know that the Gamekeepers all take bribes and you know that from time to
time one of them is executed for this activity. You’re not averse to taking
bribes yourself, you are very averse to dying which means you take great care
not to get caught.

This year, no one has tried to bribe you… yet. This means you don’t have much
of a challenge and, when you have little to occupy your mind, you get bored.
When you are bored you tend to look for sources of inebriation and flirtation.
The Games provide plenty of opportunity for either or both.

You are very aware that a Gamekeeper was executed last year for taking a bribe
to ensure the Victor came from Canton 5. Your money would have been on the
Triumph from Canton 11.

---

# {{< icon "chess-king" >}} Those of the Eternal City

## <a name="hamilton_maddox"></a>{{< icon "landmark" >}} Hamilton Maddox

*Bored corporate heir addicted to exotic intoxicants*

### What you hope for

Permanent intoxication — and not to fall too far from your family, you still need their money

### How you got here

Born in the Eternal City you led a life of privileged boredom. Your family’s
corporate business provides you with wealth but holds no interest for you and
you involve yourself in it as little as possible. You escape boredom by
indulging in various intoxicants, the more exotic and expensive, the better.
Of course, your family do not approve of this activity. Especially as it makes
you dependent on some rather despicable characters who provide you with ever
more expensive pharmaceuticals.

A while back Indigo Smith approached you and threatened to inform your family
of your addictions unless you worked for them. Well, working for them suits
you quite well. You supply pharmaceuticals to your peers (and others), you get
your own supply for free and get to attend all the best parties. Like this
one.

Downwater pharmaceuticals recently approached you to see if you would be
interested in helping them test a new drug they have invented. You’re thinking
about that.

Of course, you are able to source performance enhancing drugs which might be
of interest to the Triumphs and their mentors. You could also reduce the
performance of a Triumph — if the price was right. You heard through the
grapevine that Mentor Silent Silver became Victor through the judicious use of
pharmaceutıcals — though this is not generally known. They might be interested
in a similar package for one of their Triumphs, assuming they can find someone
who can afford to pay.

---

## <a name="arundel_cambourne"></a>{{< icon "landmark" >}} Arundel Cambourne

*Shallow socialite*

### What you hope for

Love and romance

### How you got here

You were born and raised in the Eternal City so, of course, you consider
yourself to be better than any underling from the Cantons. You do not ‘work’,
your family are able to keep you in the lap of luxury. The Games are your
favourite time of year. So much fun! All the peasants in from the Cantons, the
colours, the excitement and of course The Triumphs. Last year you enjoyed a
whirlwind romance with the Triumph from Canton 3. They were not much of a
conversationalist, but the sex was sensational and all the more poignant
because you knew the affair would be short lived. Well, it had to be — your
father would not tolerate you taking up with someone from any of the Cantons,
especially one of the poorer ones, even if they were a Victor. You have been
eyeing up the Triumphs as they appear. You would love to repeat the experience
with a new lover — so romantic!

You have recently met Trebizond Pretzel and taken them under your Wing. They
seem so sweet and naïve but, at the same time, you see yourself in them! You
think the Mentor Barley Cropper has taken a liking to you. Maybe they even
have a bit of a crush on you. This is touching but they have such a terrible
reputation! Which is, of course, exciting in itself.

A minor problem is that you are pretty sure your family have paid someone to
keep an eye on you and ensure that you don’t get yourself into trouble,
they’ve done that before. But what fun would the Games be if you couldn’t go
off the rails just a little?

---

## <a name="zephyr_baradras"></a>{{< icon "landmark" >}} Zephyr Baradras

*Poor little rich kid idealist*

### What you hope for

To join the rebels, help organise them and make a fairer society

### How you got here

You were born with a silver spoon in your mouth. Daddy always bought you
everything you wanted. He bought things for Mummy too, but mostly all she
wanted was to get stoned or drunk on the latest intoxicant. Though, to be
fair, she always managed to look good on his arm, at least for the first hour
or so of any event (after which she would need a lie down). Daddy got you a
ticket to this event in the hope that you would find yourself a suitable
spouse.

But you have always had a rebellious nature. Oh, you understand that most
people would consider you to be extremely lucky, but you know in your heart
that the system that produced your privilege is profoundly unfair. Things need
to change, and you have access to the cash and the influence to change them.
You have joined a secret movement, active in the Eternal City, who want to see
change. They are still getting organised and there is much debate about
whether they should work for reform or revolution — you’re not sure which of
those you’d prefer. They don’t really trust you yet, due to your background,
so your mission here is some sort of test.

You recognise Munroe Wright. Their father was one of the original members of
your movement but got himself banished back to Canton 6 for speaking against
the Triumvirs.

Your mission here is twofold. Firstly, you are aware that one of the leaders
of the movement is here, working in deep cover. You are to keep an eye out for
any threats to them and find some way of warning them should any such threats
arise. You are also here on a recruitment drive though, naturally, you have to
be =very= careful who you approach. The poor-little-rich kid cover is
something you can carry off without thinking.

---

## <a name="lennox_downwater"></a>{{< icon "landmark" >}} Lennox Downwater

*Corporate heir, adrenaline junkie with gambling debts*

### What you hope for

To pay off some of your debts

### How you got here

You were born and raised in the Eternal City. You have a nice little position
in your family corporation (Downwater Pharma) but it doesn’t bring in the
amount of money you need to meet your gambling debts, nor does it provide the
kind of excitement that only comes at the gaming tables. You instinctively
know that you are just better than anyone from any of the provinces. Maybe you
don’t have as much education or talent but being born into an elevated family
is worth more than any knowledge or ability. It is all that matters. Sadly,
your family do not appreciate you. The firm promoted Ellis Silver, some
jumped-up  nobody from Canton 7 ahead of you. Your uncle (who is head of the
Corporation) complains about your gambling debts. He says you cost the
Corporation too much money and are bad for their reputation.

You owe a lot of money to Indigo Smith. They often get you to do favours for
them to help pay off your debts. This weekend they asked you to keep an eye
out for Filimore Partridge who has recently arrived in the Eternal City from
Canton 4. You’re not sure what they are doing for Indigo, but your task is to
help them ‘act like a toff’. Well, Indigo is on the board of Maddox
Corporation, but Filimore has just arrived from some province or another and
you are pretty certain they are not entirely what they seem.

You love to gamble. But it’s not enough just to place bets on the Triumphs.
This year you are running a book. You will have to set the odds carefully as,
regretfully, you’ve reached the limits of your allowance, your debts are
mounting, and you cannot afford to lose money. If it looks like the ‘house’ is
going to take a loss on the Games, you will have to nobble one or more of the
Triumphs.

One thing you know that your rival, Ellis Silver does not. Downwater provided
Silence Silver with something they used to win the games. That’s a secret, and
a valuable one. You need to ensure that it comes out in a way that is
maximally advantageous to you. And preferably in a way that makes the official
rep look foolish. Or maybe you could blackmail the mentor or find some other
way to profit.

---

## <a name="caroly_wendelsmith"></a>{{< icon "landmark" >}} Caroly Wendelsmith

*Next in line for the Throne*

### What you hope for

To get out from under your father’s influence and do the right thing.

### How you got here

You have vague memories of living in Canton Five with two parents. Your
parent, Castor Smith, brought you to the Eternal City when you were very
young, and you grew up here as part of a one parent family. If you can call it
that — your single parent is always busy with some sort of business or other
and you know their employees only treat you well because they are afraid of
them. Everyone is afraid of your parent. You are terrified of them. You know
they want to be the only ruler of the Imperium and that they want you, or
maybe a younger sibling, as yet unborn, to succeed them. You also know that
this is not how things are done in the Imperium and that changing things to be
the way your parent wants them to be would involve a great deal of bloodshed
and hardship. Maybe even a war!

You are, really, stuck between a rock and a hard place. You believe that what
your parent wants is wrong, but you can’t see a way to stop them. Especially
as you are so afraid of them, and the thugs with whom they surround themself.
Maybe, if you go along with their plans (and, in the event that they succeed),
you could turn the Imperium into a better place. That is what Triumvir Gold
seems to want to do. They’re kind of a mentor figure to you — someone in whom
you might be able to confide — but you’ve not approached them about your
parent’s ambition yet. Triumvir Gold is always determined to see the best in
everyone.

It irritates you that everyone always underestimates you and assumes that you
will support your parent whether they are right or wrong. You think it’s
important to do the right thing, even if that means betraying your parent.

Of course, if your parent knew this, they would get rid of you and raise a
younger, more compliant sibling in your place.

---

## <a name="porphyry_mendleson"></a>{{< icon "landmark" >}} Porphyry Mendleson

*The richest person in the Universe*

### What you hope for

To keep the status quo, whatever the cost

### How you got here

You are the CEO of Downwater Pharma and Baradras Pharmaceuticals. Even within
the eternal city few know that these apparent ‘rival corporations’ belong to
the same family. Yours. There are a lot of things that are not as they seem.
The triumvirate think they run things in the Imperium. The ignorant masses
agree with them and think the whole bureaucratic structure that supports them
in their apparent power is effective. You know better. It is the corporations,
lifeblood of the Eternal City which hold the true power

If the Triumvirate had power, why would anyone allow a petty criminal from
Canton 5 to rise to their ranks? A half blind bureaucratic sybarite from
Canton 2? It’s true that the other Triumvir is from the Eternal City — their
function is to remind the other two of their place — but Hedony Melody has
not been seen for some months. You believe they are ill and will soon need
replacement. You have your eyes wide open for a likely replacement, preferably
a Mendleson.

It is absolutely essential to keep the status quo of power in place. It is
absolutely essential that no one outside the Eternal City understands that the
whole thing is a sham. Like most of your peers, you consider the Games to be a
deadly bore. The CEOs, however, do take it in turns to oversee the rituals in
person. You leave the actual competition to subordinates, of course, why would
you wish to get your hands dirty?

There are two main threats here. One is the nascent rebel movement — rebels
are always around but you need to make sure they cannot organise or grow. The
other is Triumvir Castor Smith who, so rumour goes, wishes to make himself
Emperor and have his offspring follow him.

The younger generation of the corporations are a worry… Arundel Cambourne,
Lennox Downwater, Hamilton Maddox and Zephyr Baradras. You can use their
antics to embarrass their families and keep the lesser corporations in line.
That said, you would use your wealth and influence to save them from
execution, if it came to that  — banishment would be a better solution.

You can also call on Bowie Fisher, the official head of security here. They
believe you to be a senior member of their organisation and should do anything
you ask of them.
