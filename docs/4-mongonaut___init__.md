# Mongonaut Init

[_Documentation generated by Documatic_](https://www.documatic.com)

<!---Documatic-section-Codebase Structure-start--->
## Codebase Structure

<!---Documatic-block-system_architecture-start--->
```mermaid
None
```
<!---Documatic-block-system_architecture-end--->

# #
<!---Documatic-section-Codebase Structure-end--->

<!---Documatic-section-mongonaut.__init__.get_version-start--->
## mongonaut.__init__.get_version

<!---Documatic-section-get_version-start--->
<!---Documatic-block-mongonaut.__init__.get_version-start--->
<details>
	<summary><code>mongonaut.__init__.get_version</code> code snippet</summary>

```python
def get_version():
    version = '%s.%s' % (VERSION[0], VERSION[1])
    if VERSION[2]:
        version = '%s.%s' % (version, VERSION[2])
    return version
```
</details>
<!---Documatic-block-mongonaut.__init__.get_version-end--->
<!---Documatic-section-get_version-end--->

# #
<!---Documatic-section-mongonaut.__init__.get_version-end--->

[_Documentation generated by Documatic_](https://www.documatic.com)