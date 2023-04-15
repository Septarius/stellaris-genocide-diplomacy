# Septarius' Driven Assimilator, Determined Exterminator, Devouring Swarm, and Fanatic Purifier Diplomacy

Allow the Driven Assimilators, Determined Exterminators, Devouring Swarms and Fanatic Purifiers in your life to be able to co-op with you. Not all alone in the dark galaxy brooding and plotting your demise.
This allows all known diplomatic actions, all galactic wide events (community, empire, council, market, vassels) and trade with the artisans and traveling merchants.

Include's the stop spam / shut up modifers for the actions that were modified. This way, this mod can be used without causing spam. If you want to use this mod and have spam, (not sure why), feel free to make an override mod.
For the rest of the spam reduction see: StopSpam https://steamcommunity.com/sharedfiles/filedetails/?id=2933806344 or "Shut Up We Don't Care" [Currently not supported in this patch]

If other mods override these specific actions/events would require a compatibility patch to function.

Overrides:
common\diplomatic_actions\00_actions
    action_improve_relation
    action_harm_relation
    action_offer_trade_deal
    action_make_rival
    action_form_defensive_pact
    action_form_non_aggression_pact
    action_form_commercial_pact
    action_form_research_agreement
    action_guarantee_independence
    action_support_independence
    action_form_migration_pact
    action_offer_federation_association_status
    action_ask_for_federation_association_status
    action_invite_to_federation
    action_ask_to_join_federation
    action_open_borders
    action_demand_subjugation
    action_ask_to_become_subjugated
    action_embassy
    action_pledge_secret_fealty
    action_propose_secret_fealty
    action_reveal_presence
    action_societal_enlightenment
    action_open_technological_enlightenment
    action_pre_ftl_trade

common\game_rules\00_rules
    can_release_vassal
    can_use_galactic_market
    can_be_part_of_galactic_community
    can_be_part_of_galactic_empire
    can_be_part_of_galactic_council

events\caravaneer_events.txt
events\federations_events_3.txt
events\leviathans_events_1.txt