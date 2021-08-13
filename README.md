# Smart contract hacking challenge

> Challenge introduced in my ["7 phases of smart contract security" talk](https://www.youtube.com/watch?v=gGUOjtri4n8) at DEF CON 28 in the Blockchain Village

This challenge involves governance and flash loans. What could go wrong, right ?

You must steal all tokens from the `Pool` contract.

- [See contracts](contracts/)
- [Go to challenge script](test/exploit.js)

## How to play

1. Clone this repository
2. Install dependencies with `npm install`
3. Code your solution in the provided `test/exploit.js` file
4. Run with `npm run challenge`

### Tips

- You must use the `attacker` account. That is, all your transactions should include `{ from: attacker }`.
- Solve the challenge by coding your script in the highlighted `it` block of the `test/exploit.js` file.
- Do not not modify anything else. The script already takes care of setting up the scenario and checking success conditions.
- If you need to use an attacker contract, add it in the `contracts` folder.

Related documentation you might find useful:

- [OpenZeppelin Test Helpers](https://docs.openzeppelin.com/test-helpers/0.5)
- [Truffle Contracts API](https://www.trufflesuite.com/docs/truffle/reference/contract-abstractions)

## Maintainers

Created and maintained by [@tinchoabbate](https://github.com/tinchoabbate)

## Disclaimer

All Solidity code, practices and patterns in this repository are vulnerable and for educational purposes only.

DO NOT COPY. DO NOT USE IN PRODUCTION.
