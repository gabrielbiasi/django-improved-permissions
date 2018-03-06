Shortcuts
=========

Checkers
^^^^^^^^

.. function:: has_role(user, role_class, obj=None)

Returns True if the user has the role to the object.

.. function:: has_permission(user, permission, obj=None)

Returns True if the user has the permission.

Assigning and Revoking
^^^^^^^^^^^^^^^^^^^^^^

.. function:: assign_role(user, role_class, obj=None)

Assign the role to the user.

.. function:: assign_roles(users_list, role_class, obj=None)

Assign the role to all users in the list.

.. function:: remove_role(user, role_class, obj=None)

Remove the role and your permissions of the object from the user. 

.. function:: remove_roles(users_list=None, role_class, obj=None)

Remove the role and your permissions of the object from all users in the list.


Getters
^^^^^^^

.. function:: get_user(role_class=None, obj=None)

Get the unique user instance according to the object.

.. function:: get_users(role_class=None, obj=None)

Get the all users instances according to the object.