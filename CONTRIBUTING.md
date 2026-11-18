# Contributing

This guide covers every repository of the TandemLLM organization that has no CONTRIBUTING.md of its own (TandemEngine has one with its engine rules).

Thank you for helping. Bug reports, measurements and pull requests are welcome.

## Before a pull request

- Run the repository's tests: its README says how (TandemApp: `python3 tests/script_suite.py --all`, and in `dashboard/`, `npm ci && npx vitest run`). All of them must pass.
- Keep a pull request to one change, with a test for it.
- Commits, docs and the CHANGELOG are written for a reader of the public repository: facts, commands, and each number with its conditions. No private hostnames, home paths or personal notes.

## Contributor License Agreement

TandemLLM is dual-licensed: AGPL-3.0 for everyone, and a commercial license from the copyright holder (each repository's COMMERCIAL-LICENSE.md: [TandemEngine](https://github.com/TandemLLM/TandemEngine/blob/main/COMMERCIAL-LICENSE.md), [TandemApp](https://github.com/TandemLLM/TandemApp/blob/main/COMMERCIAL-LICENSE.md)). To keep that possible, every contributor must agree to the Contributor License Agreement below before a pull request is merged. To agree, add this sentence to your pull request: "I have read the Contributor License Agreement in CONTRIBUTING.md and I agree to it."

### Contributor License Agreement

1. "You" means the person or legal entity submitting a contribution. "Contribution" means any code, documentation or other material you submit to this repository. "Maintainer" means Khaled Bakeer, the copyright holder of TandemLLM.
2. You keep the copyright in your contribution.
3. You grant the Maintainer and anyone who receives software from the Maintainer a perpetual, worldwide, non-exclusive, royalty-free, irrevocable license to use, copy, modify, publish, distribute, sublicense and relicense your contribution, under the AGPL-3.0 or under any other license, including commercial licenses.
4. You grant the same parties a perpetual, worldwide, non-exclusive, royalty-free, irrevocable patent license for any patent claims you can license that your contribution needs, to make, use, sell and distribute the contribution alone or as part of TandemLLM.
5. You confirm that the contribution is your own work, or that you have the right to submit it under these terms. If your employer has rights in your work, you confirm that it allowed you to submit it.
6. You are not expected to support your contribution. It is provided "as is", without warranties of any kind.
