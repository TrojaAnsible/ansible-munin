Role Name
=========

installs munin-node and activates docker plugins

Requirements
------------


Role Variables
--------------
| defaults variable | description |
|-------------------|-------------|
| git_home| base path into which the repository is cloned|
| github_base_url| github domain name 'https://github.com'|
| github_repo|repo name|
| github_url|git clone url|
| munin_plugins_active|munin plugins directory|
| munin_plugins_conf|munin config directory|
| munin_plugins_home|installation path for munin plugins|
| munin_plugins_name|list of plugin names|
| munin_plugins_wildcard_src_name|wildcard plugin name|
| munin_plugins_wildcard_tgt_name|wildcard plugin suffix|
| repo_dir|directory in git repository where the plugin is located|


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-munin }

License
-------

This project is licensed under the Attribution-NonCommercial-ShareAlike 4.0 International License - see the [LICENSE.md](LICENSE.md) file for details

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
