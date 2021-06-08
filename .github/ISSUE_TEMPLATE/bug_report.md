---
name: "\U0001F41B Bug report"
about: Create a report to help us repair something that is currently broken
labels: bug

---
<!-- Thank you for contributing. These HTML comments will not render in the issue, but you can delete them once you've read them if you prefer! -->

### Bug description
<!-- Use this section to clearly and concisely describe the bug. -->

#### Expected behaviour
<!-- Tell us what you thought would happen. -->

#### Actual behaviour
<!-- Tell us what actually happens. -->

### How to reproduce
<!-- Use this section to describe the steps that a user would take to experience this bug. -->

1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

### Your personal set up
<!--
Tell us a little about the system you're using.
Please include information about how you installed,
e.g. are you using a distribution such as zero-to-jupyterhub or the-littlest-jupyterhub.
 -->

 - OS:
 <!-- [e.g. ubuntu 20.04, macOS 11.0] -->
 - Version(s):
 <!-- e.g. jupyterhub --version, python --version --->

- <details><summary>Full environment</summary>
<!-- For reproduction, it's useful to have the full environment. For example, the output of `pip freeze` or `conda list` --->

```
# paste output of `pip freeze` or `conda list` here
```
</details>

- <details><summary>Configuration</summary>
<!--
For JupyterHub, especially include information such as what Spawner and Authenticator are being used.
Be careful not to share any sensitive information.
You can paste jupyterhub_config.py below.
To exclude lots of comments and empty lines from auto-generated jupyterhub_config.py, you can do:
    grep -v '\(^#\|^[[:space:]]*$\)' jupyterhub_config.py
-->

```python
# jupyterhub_config.py
```
</details>

- <details><summary>Logs</summary>
<!--
Errors are often logged by jupytehub. How you get logs depends on your deployment.
With kubernetes it might be:

    kubectl get pod # hub pod name starts with hub...
    kubectl logs hub-...
    # or for a single-user server
    kubectl logs jupyter-username

Or the-littlest-jupyterhub:

    journalctl -u jupyterhub
    # or for a single-user server
    journalctl -u jupyter-username
-->

```
# paste relevant logs here, if any
```
</details>
