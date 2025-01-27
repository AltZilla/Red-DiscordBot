.. red's core utils documentation

=================
Utility Functions
=================

General Utility
===============

.. automodule:: redbot.core.utils
    :members: deduplicate_iterables, bounded_gather, bounded_gather_iter, get_end_user_data_statement, get_end_user_data_statement_or_raise, can_user_send_messages_in, can_user_manage_channel, can_user_react_in

.. autoclass:: AsyncIter
    :members:
    :special-members: __await__
    :exclude-members: enumerate, filter

    .. automethod:: enumerate
        :async-for:

    .. automethod:: filter
        :async-for:


Chat Formatting
===============

.. automodule:: redbot.core.utils.chat_formatting
    :members:
    :exclude-members: pagify

    .. autofunction:: pagify(text, delims=('\n',), *, priority=False, escape_mass_mentions=True, shorten_by=8, page_length=2000)
        :for:

Embed Helpers
=============

.. automodule:: redbot.core.utils.embed
    :members:
    :exclude-members: randomize_color

Menus
=====

.. automodule:: redbot.core.utils.menus
    :members:

Event Predicates
================

MessagePredicate
****************

.. autoclass:: redbot.core.utils.predicates.MessagePredicate
    :members:

ReactionPredicate
*****************

.. autoclass:: redbot.core.utils.predicates.ReactionPredicate
    :members:

Mod Helpers
===========

.. automodule:: redbot.core.utils.mod
    :members:

Tunnel
======

.. automodule:: redbot.core.utils.tunnel
    :members: Tunnel
    :exclude-members: files_from_attatch

Common Filters
==============

.. automodule:: redbot.core.utils.common_filters
    :members:

Utility UI
==========

.. automodule:: redbot.core.utils.views
    :members:

AntiSpam
========

.. automodule:: redbot.core.utils.antispam
    :members:
