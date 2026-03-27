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

## Adventurer Pull Plans

??? note "TheAxolotl's Pull Plan"

    I'll try to pull for a few copies and experiment with her as an adventurer herself, not just as an inherit. Plus, Bard was probably my favorite class in Wizardry 8, and she's the closest we have to that at the moment!

 
## Duplicate Usage

* Inherit to herself to increase the buff magnitude
* Inherit to someone else
* Discipline will slightly boost her action speed and SP

{% endblock ReviewsAndAnalysis %}