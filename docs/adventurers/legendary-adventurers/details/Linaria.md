---
# Just change title to character's name, should match filename, and all data
# fields will pull from adventurers.csv, skills.csv, and image folder. 

   title: Linaria

# Note image files are all lowercase, and are expected as:
# name-class.jpg, name-altform.jpg, name-class-personal-request.jpg
#
# Free text can still be added to any section in the relevant text block but
# skill text still needs to be indented 8 spaces.
#
# Reviews can be added at end be removing comments around relevant sections
# in free text block.  To not remove any block tags.  

# set debug parameter to true to save full markdown before HTML build
# in a {project_dir}/debug_output folder (if that folder exists)
   debug_render: false  

---
  
{% extends "Adventurer_parent.md" %}   
     
{% block InheritFreetext %}
{% endblock InheritFreetext %} 

{% block AltInheritFreetext %}
{% endblock AltInheritFreetext %}
     
{% block PotentialInheritFreetext %}
{% endblock PotentialInheritFreetext %}

{% block UniqueSkillFreetext %}
{% endblock UniqueSkillFreetext %}

{% block AltUniqueSkillFreetext %}
{% endblock AltUniqueSkillFreetext %}

{% block DisciplineFreetext %}
{% endblock DisciplineFreetext %}

{% block AltDisciplineFreetext %}
{% endblock AltDisciplineFreetext %}

{% block ReviewsAndAnalysis %}

<!-- any Character Reviews and pull plans go down here. Just uncomment sections -->

## Adventurer Reviews

??? info "TheAxolotl's Analysis"

    One thing I've really been pleased with about this game is that the devs do a great job of releasing strong and/or unique adventurers without making them game-breakingly broken. Linaria is a good example of this - many initial reactions were that she's very overpowered, but that's not really the case, and whether or not you use her is ultimately going to boil down to what you want in your party. Let's look at her skills!

    First, Riotous Ballad is her buff, and it's quite solid. First and foremost, it's a true damage buff and not an attack power buff, so this has the benefit of boosting magic damage as well as physical damage. While most parties don't run with heavy magic damage, there are some exceptions out there and this will become even more valuable if magic damage ever gets a rework by the devs. As with most buffs, this is not a flat percentage multiplier - there's a multiplicative as well as an additive component. Early testing shows that at skill level 1 on Linaria herself, the buff is somewhere in the order of a 10% increase plus a flat 45ish damage. Inheriting the skill seems to reduce the flat component more than the percentage component, but it's a bit tough to say for sure and will need some more testing to iron out.

    As far as practical application, Riotous Ballad will generally perform better for lower attack power, multiple hit weapons than it will for high attack power, single hit weapons, just due to the flat portion of the boost being more noticeable at lower power levels. One important thing to note is that Riotous Ballad does not buff a single row - rather, it buffs the two adventurers on either side of the user plus the adventurer in front or behind the user. For optimal positioning, this means you want Linaria to be placed in either the front or rear middle party slot. As an example, if I were to run her in my party, I could position her as follows:

    Shiou - Linaria - Rinne<br>
    MC - Yuzu - Sheli

    This would enable Shiou, Rinne, and Yuzu to all receive a damage boost. The fact that the buff does not care about alignment is pretty great, and makes it comparable to the Prayer of Rebellion value. Speaking of PoR, it does stack, but it also takes up a standard buff slot, so you'll have to keep an eye on your buffs so you don't accidentally knock off something important.

    Her next skill, Encore, appears to be roughly a 50% change to trigger during the first turn. A key thing to note here is that Encore will only trigger on skills. This means that inheriting something like PORTO to her and doing PORTO -> Encore -> Riotous Ballad is not possible. However, it does allow for something like Riotous Ballad -> Hiding.

    As far as Discipline goes, she gets ASPD and SP as her featured stats, which does lean into her support-heavy focus.

    One of the big downsides to her kit is that she's a Thief class, which generally performs on the weaker side in combat these days. Her Encore skill does open up some interesting potential with class changes, but it's hard to say what value that will have at the moment.

    One neat thing is that in camp, she does play her lute and provide some music, which is a nice little aesthetic touch!

??? info "Shiro's Analysis"

    So as people expected we got thief with lute… I want to praise devs on start for visual design and the audio coming along with this character. It surely is a really nice add-on to the game and will be highly appreciated by some people.

    But now going to practice, she’s dark element which is the best option for thieves, followed by the human race, so nice luck growth on top of the dark element already supporting it, which means solid stats for chest opening. 

    Her passive is kind of nice… but I’m not that big fan of heavy RNG in fights so I’m not losing my mind over it and I find it whatever… unless she’ll get knight later on which can be a really interesting option.

    Her discipline is ASPD and SP which push her more into the support side which is something I’m really happy about too, Devs did know what to do with it this time.

    The interesting thing is her inheritance. It’s not ATK or MATK buff but ALL DMG UP. What does it mean in practice? First it’s active so it’s not worse than passive Lana and Alice in that matter, secondly it buffs characters that are next to her not including her, which means you can pick whichever 3 units you want to buff, cutting her off while she’s supported anyway so no buff slot is wasted. Lastly there’s no personality requested unlike in case of Lana or Alice. And also I might call it kind of future proof thanks to it. Might be better to grab her mainly for inheritance over character and just feed it to Alice. Especially looking how for example Dwarf Cave boss shows that devs might want us to stack damage buffs and supports and focus on 1-2 DPS.

    Overall in my opinion the new character is really good with the main selling point being her inheritance. Her being a thief is even better because she can reach high ASPD and have better rotations. And in my opinion thieves are better as controllers and sub-dps or full supports with main selling point being delay and all kind of status/debuff skills supporting your main DPS over thieves doing DMG themselves, which Linaria leans towards, so while I wouldn’t pull for her or go crazy over her I’m really happy that developers know what they are doing.


??? info "Karkarov's Analysis"

    We are back in 2024 baby!  We have a new legendary and they are evil alignment and dark element!  Drecom is back to their favorite combo!  Jokes aside, what is the story on Linaria the thief?

    Well she is a female, dark element, evil, thief as stated.  So immediately we have some conclusions, 1: she does not work well on the front line.  Not only because she does not play well with the Lana buff, but she is in fact a thief too.  As a class thief does best on the back row with a bow.  2: the synergy is very hit or miss.  Dark element doesn't really do anything good for thief.  Female characters get a speed buff, but no strength or dex.  If her class had been mage this would have been a very solid set up though, priest would have been ok too.  That said she clearly does fine on the back row so works with the Alice buffs, and can stand beside Yuzu which does matter in this case and we will get to that later.  To round it out her discipline is speed and SP which is pretty solid, not blowing the doors off but could have been a lot worse.  A good discipline for a support oriented character and that is what Linaria really is..... insert record scratch here as now we see the elephant in the room.  Thief (unless you count opening boxes and increasing money drops in auto farms) basically has no support skills, but she is clearly designed as a support character.

    So to understand why she is designed to actually be a support we have to look at her unique skill, and her passive inherit skill.  First lets talk about the inherit skill Riotous Ballad.

    Ballad is a damage buff skill (this is important, skills use sp etc etc) that effects the person in front/behind of Linaria, and anyone to her right or left.  This means it can impact up to 3 characters, but not 3 characters in a row, and not Linaria herself.  It is a true support skill as it does nothing for our actual skill user.  So how good of a damage buff is it?  Is it 30%? That's what that japanese clickbait video said Kark!  90% at level 7 baby ahahahahahahahaha~~???!!!!! No.  It is not 30%.  It is not 20%.  I am not even totally sure it is 10%.  I am still doing data gathering and working on trying to sus it out in a meaningful way.  There is a chinese player who did some real study on it and suggested it is 40 flat bonus + 9%, but when this is applied to some of my data it doesn't hold water, though this is closer than anything else I have seen thrown around on reddit or discords.  Here is a [LINK](https://forum.gamer.com.tw/C.php?bsn=70180&snA=4146&tnum=2) to the site if anyone wants to look at the data themselves, bear in mind it is in chinese.

    So you did testing, you are saying the early numbers were massibely overblown and wrong, thats great, whats the point?  Ok, so as I mentioned I am not sure of the exact formula yet it needs more testing.  What I can say 100% for sure is that Ballad is not a flat % gain.  It is some degree of + static value and + percent.  Most likely the % is actually fairly low, probably 10% or less.  I am suspecting it is probably like a 25-75 or 40-60 (flat / percent) split where a good chunk of the extra damage is coming from a flat value.  Testing by some discord users (thanks Gagging and Topbird) and testing in the trial battle STRONGLY suggest leveling the skill past 3 does mostly nothing, and most of the bonus you get from leveling the skill is a flat + value, not a percent increase.  So leveling the skill very far is not a great idea.

    What does that mean OMG~!!!?!?!?!?  It means in short, ballad is kind of like a newb trap skill.  At low level, in early content, that flat bonus is doing a lot of lifting and results in these numbers that make people mistakenly believe it is a 30%ish increase.  Because a large portion of the bonus comes from a flat number though.... this means the bonus gets less, and less, and less impressive the further you get in the game.  In my testing I was seeing bonus damage on level 1 as low as 130 damage on average.  For a level 70 character in abyss 4 130 damage is not rustling any jimmies.  Now this is a per hit increase though so of course we have to throw a bone and go back to what I said earlier.... it is really good if she is standing beside Yuzu.  Cause again, per hit, large portion is a flat bonus = favors multi hit attacks.  Aka - huehuehuehuehuehue.  This also means for this skill to really be a meaningful value add you basically have to pair her with a hue user that has a hairpin.  Thanks Drecom.  
    
    Even then, it is really only benefitting one character that is already not having any damage problems to begin with.  In fact I doubt you get more damage on hairpin hue from this than you would if you just used a spear fighter instead and did say splitter level 3 or poised once.  In short the value of this skill is not what it first seemed and it is kind of a big "so what?"  Unless of course you are a whale with 3 hairpins and 3 ninja who have hue 3 or better.  In that case it's slobberin time boys pull pull pull, it isn't like your money is a limited resource anyway.

    Oh and PS, testing by others suggests it's effectiveness is at least 40% lower total bonus as an inherit than on Linaria herself... so if I am saying it isn't that impressive on the actual character you can be sure it isn't winning any awards as an inherit.  Prayer of Rebellion is simply a better damage buff, more readily available (adventurer bones II), and easier to use.

    Ok so Ballad is not looking as great as it seemed in the first clickbait vidoes (shocking) and it scales poorly as you progress through the game.  What about Encore?  Encore in my opinion was always the lynch pin skill of this character and was extremely interesting on paper.  If it worked like a quick glance suggested this character would be VERY strong as a support, like, possibly the best in the game.  Too bad it doesn't work like a first glance suggested.

    So Encore does have some good things going for it. First what does it do?  It is a passive that on a leveled Linaria (lets say 50 or higher) has a proc rate of give or take 50%, and when it procs Linaria gets an immediate free turn.  At lower level (20 or lower) I found the proc rate was more 25'ish%, but that isn't really important as it improves long term assuming I didn't just have a terrible luck run.  How do you proc it?  Easy, it may proc when using a skill that buffs or debuffs, the skill cannot do any damage not even 1 point.  It can even proc more than once in one round (theoretically) but my testing suggested the proc rate of twice in one round was so low we may as well just say it is 10% or lower.  I never saw it proc 3 times in one round though the skill implies it can.  Yes I inherited enough skills to try for that.

    So clearly something is wrong right, you give that impression?  Yeah quite a bit actually.  First it comes down to "it may proc when using a skill that buffs or debuffs...".  So not when you use an item.  Not when you use a spell.  Not when you do ANYTHING that might result in the enemy taking any form of damage.  With this in hand you realize... the list of things that can proc this skill is extremely small.  Not only that, thief only has 1 native skill that can actually proc this ability... the mostly useless at this point in the game "Hiding".  Couple this with the fact that you cannot repeat actions and most skills that coupld proc this either can't be inherited or are class restricted... and you will have a hard time finding skills worth using to proc it at all.  
    
    Right now the only options to inherit that Linaria can actually use and proc this skill are Warrior's Battle Cry, Self Healing, Defensive Provoke (you want your thief on the front line using a dagger right?), Black Beast Feint (keep pulling aggro on your thief), and Lingering Blossom (put enough aggro on your thief yet?  Meanwhile def worth sacking a Shiou for this).  I guess the Gerard alt "Requietal by Blade" MIGHT work to proc it too, but I am not going to test that and you shouldn't either. 

    So it is a 50/50 if it even procs, even if you have a second skill to use that could proc it the rate of double proc is extremely low, and other than her own skill Ballad there really is no great skill to use to proc it.  Battle Cry is ok since she should be back row and eventually you will actually attack I guess?  If she had ninja it would be great with shedding, dissipation, or voice theft.  Even as a mage she could have luck fished with a mental unity into an attack spell.  But she is a theif, so nah, you buff with Ballad, maybe proc it, then you ... ... ... hope to have inherited something worth doing for your free turn?

    If you aren't seeing the problem it is pretty simple.  While Ballad is ok, it isn't actually anything special and due to it being "adjacent" allies is kind of clunky to use.  Meanwhile you wont use Ballad every round regardless since it can't be "targetted" so you wont have it for proccing Encore a good amount of the time anyway.  So the usefulness of Ballad is so so, Encore is too limited in what can proc it, and as a thief she is highly reliant on large amounts of very limited inhertis to have good attack options such as wide volley, moment of finality, decisive torso strike, challenger strike, etc.  Hell she is highly reliant on inherits just to have something worth using to proc Encore at all other than ballad which you dont need to use every round. 

    I apologize for this write up being so long, but I did do hours and hours of testing and I really did want to find an excuse to like this character.  I mean the design aesthetics are fantastic both in visuals, her personality, and the great voice work in english and japanese.  Her playing the lute in camp and tavern is such a nice touch and great bit of character flair.  But her two skills bounce between being ok but nothing special, and extremely limited in how they can even be used.  Ultimately she is held back by her class, she needed to be something more support oriented that could benegit from an SP dump like mage or priest, or ninja that has multiple SP based buffs/debuffs.  
    
    In the end TLDR: As of 3/28/26 I can't recommend you pull this character for anything other than her visual and audio design.  She is the wrong class for her support oriented design intent, this results in poor synergy as a character, and makes it hard to justify fitting her into an existing team.  She needs too many inherits to really get cooking, and many of the ones I would recommend are even highly limited and hard to get.  Ballad as an inherit is not good enough to really consider spending resources on either unless you just have them to burn.  Just like Raffaello she is a "wait and see" character where the value won't really be seen until her second class is revelead.  Lets hope that when that reveal happens, unlike with Raffaello, the second class actually is a good fit for her as a character.

    

## Adventurer Pull Plans

??? note "TheAxolotl's Pull Plan"

    I'll try to pull for a few copies and experiment with her as an adventurer herself, not just as an inherit. Plus, Bard was probably my favorite class in Wizardry 8, and she's the closest we have to that at the moment!

??? note "Karkarov's Pull Plan"

    TLDR: It was immediately clear to me I needed to pull this character if for no other reason than to conduct my own testing.  The data I was seeing was too chaotic, based on cherry picking, very low like single digit sample sizes, and I just didn't trust it.  96 pulls later I finally got one copy.  Don't pull 96 times for this character.  From a mechanics perspective, don't even pull once.

    More detail: Linaria from an aesthetics perspective is Drecom firing on all cylinders.  She looks sexy, she has a cool detailed outfit, she plays the lute in camp, sings about how hungry she is when she wants to go to the tavern, and it is all very cool.  If you want to pull because this design is just great, you know what?  You are right. Her design is absolutely great, go for it, pull one copy.  Good luck, and I hope you dont need 96 pulls.  For people who wont pull unless there is a gameplay justification... wait for her second class to be revealed.  Ballad is not good enough as an inherit for me to justify suggesting potentially 50 plus pulls worth of effort to get it by the odds.  Meanwhile Linaria has too many limitations and needs too much investment for me to justify saying you should use her as a character in your party in her current form as of writing this on 3/28/26.
 
## Duplicate Usage

* Inherit to herself to increase the buff magnitude
* Inherit to someone else
* Discipline will slightly boost her action speed and SP

{% endblock ReviewsAndAnalysis %}
