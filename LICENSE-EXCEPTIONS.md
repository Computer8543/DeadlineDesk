# License Exceptions for Proprietary Workflow Extensions

This project is licensed under the GNU Affero General Public License, version 3 (AGPL-3.0).  
The following clarifications are provided for how this license applies in the context of proprietary, internal-use workflow extensions.

## 1. Core Software
The "Core Software" refers to all files and code in the public repository, unless otherwise indicated.  
Any modifications to the Core Software that are distributed or made available over a network to others must comply with the AGPL-3.0 terms — meaning the modified source must also be made available under the same license.

## 2. Extensions via Public API
This project is designed with a public API and documented extension points that allow separate software components to integrate with the Core Software.

You may create proprietary or closed-source workflow extensions that:
- Are maintained in a separate codebase/repository.
- Communicate with the Core Software exclusively through documented APIs, webhooks, message queues, or other public extension mechanisms.
- Do not require modification of the Core Software’s source code.

Such extensions are not considered “modified versions” of the Core Software for the purposes of the AGPL-3.0, and therefore their source code does not need to be released under AGPL-3.0, provided they remain separate works.

## 3. Internal-Only Use
If you create modifications to the Core Software for **internal use only** and those modifications are never distributed or made available over a network to users outside your organization, you are not required to release those modifications. However, contributing general-purpose improvements upstream is encouraged.

## 4. No License Change
This exceptions file does not alter or weaken the AGPL-3.0 license for the Core Software itself. It exists to clarify intended usage patterns for proprietary workflow extensions in compliance with the AGPL-3.0.

---
For more details, see: https://www.gnu.org/licenses/agpl-3.0.en.html
