Ashita v3 skillchains by Ivaar ported to Ashita v4. 
- Not 100% stable. Crashes may be related to job changes when inventory is not fully loaded.
- Not fully tested with all jobs/abilities and only tested on retail.
- Added 'pos' command for setting position.

# SkillChains
### Active Battle Skillchain Display.

Displays a text object containing skillchain elements resonating on current target, timer for skillchain window,
along with a list of weapon skills that can skillchain based on the weapon you have currently equipped. 

    /sc color    -- colorize properties and elements
    
    /sc move     -- displays text box hold shift+click and drag it to desired location.
    
    /sc save     -- save settings.

    /sc pos <x> <y> -- reposition the window to the defined x, y coordinates

The following commands toggle the display information and are saved on a per job basis.

    /sc spell    -- sch immanence and blue magic spells.

    /sc pet      -- smn and bst pet skills.

    /sc weapon   -- weapon skills.

    /sc burst    -- magic burst elements.

    /sc props    -- skillchain properties currently active on target.

    /sc timer    -- skillchain window timer.

    /sc step     -- current weaponskill step information.

More settings related to text object can be found within the addons settings
