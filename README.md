# Ansible Code Snippets

The project for these snippets is being tracked in Github [ansible-vscode](https://github.com/tmichett/ansible-vscode).

## VS Code API

### Contribution Points

- [`contributes.snippets`](https://code.visualstudio.com/api/references/contribution-points#contributes.snippets)

## Using the Ansible Code Snippets

- Install the `Extension` from the Marketplace
- Use (CTRL + Space) Windows/Linux or (Control + Space) MacOS to bring up the snippets selection.
- Choose snippet you want to use.


### Snippets Purpose

The snippets provided here are to easily write and author Ansible playbooks. These snippets are for direct use in VSCode for authoring and creating various Ansible playbooks and resources.


## Snippet Previews

**ansible_playbook**

```yaml
- name: Example to setup a user and a password
  hosts: all
  tasks:
```


**ansible_task**

```yaml
  name: Install package
  yum: 
    name: httpd
    state: latest
```

