**Note:** There is a section for disputed findings below the usual findings sections

## Summary

### Medium Risk Issues

| |Issue|Instances|
|-|:-|:-:|
| [[M&#x2011;01](#m01-contracts-are-vulnerable-to-rebasing-accounting-related-issues)] | Contracts are vulnerable to rebasing accounting-related issues | 1 | 

Total: 1 instances over 1 issues

### Low Risk Issues

| |Issue|Instances|
|-|:-|:-:|
| [[L&#x2011;01](#l01-loss-of-precision)] | Loss of precision | 1 | 
| [[L&#x2011;02](#l02-safeapprove-is-deprecated)] | `safeApprove()` is deprecated | 1 | 
| [[L&#x2011;03](#l03-external-calls-in-an-un-bounded-for-loop-may-result-in-a-dos)] | External calls in an un-bounded `for-`loop may result in a DOS | 3 | 
| [[L&#x2011;04](#l04-consider-implementing-two-step-procedure-for-updating-protocol-addresses)] | Consider implementing two-step procedure for updating protocol addresses | 1 | 
| [[L&#x2011;05](#l05-decimals-is-not-a-part-of-the-erc-20-standard)] | `decimals()` is not a part of the ERC-20 standard | 2 | 
| [[L&#x2011;06](#l06-missing-checks-for-ecrecover-signature-malleability)] | Missing checks for `ecrecover()` signature malleability | 1 | 
| [[L&#x2011;07](#l07-missing-contract-existence-checks-before-low-level-calls)] | Missing contract-existence checks before low-level calls | 9 | 
| [[L&#x2011;08](#l08-code-does-not-follow-the-best-practice-of-check-effects-interaction)] | Code does not follow the best practice of check-effects-interaction | 5 | 
| [[L&#x2011;09](#l09-missing-checks-for-address0x0-in-the-constructorinitializer)] | Missing checks for `address(0x0)` in the constructor/initializer | 18 | 
| [[L&#x2011;10](#l10-missing-checks-for-address0x0-when-updating-address-state-variables)] | Missing checks for `address(0x0)` when updating `address` state variables | 7 | 
| [[L&#x2011;11](#l11-state-variables-not-capped-at-reasonable-values)] | State variables not capped at reasonable values | 1 | 

Total: 49 instances over 11 issues

### Non-critical Issues

| |Issue|Instances|
|-|:-|:-:|
| [[N&#x2011;01](#n01-public-functions-not-called-by-the-contract-should-be-declared-external-instead)] | `public` functions not called by the contract should be declared `external` instead | 116 | 
| [[N&#x2011;02](#n02-event-is-not-properly-indexed)] | Event is not properly `indexed` | 8 | 
| [[N&#x2011;03](#n03-duplicated-requirerevert-checks-should-be-refactored-to-a-modifier-or-function)] | Duplicated `require()`/`revert()` checks should be refactored to a modifier or function | 12 | 
| [[N&#x2011;04](#n04-common-functions-should-be-refactored-to-a-common-base-contract)] | Common functions should be refactored to a common base contract | 2 | 
| [[N&#x2011;05](#n05-open-todos)] | Open TODOs | 2 | 
| [[N&#x2011;06](#n06-events-that-mark-critical-parameter-changes-should-contain-both-the-old-and-the-new-value)] | Events that mark critical parameter changes should contain both the old and the new value | 2 | 
| [[N&#x2011;07](#n07-constant-redefined-elsewhere)] | Constant redefined elsewhere | 5 | 
| [[N&#x2011;08](#n08-lines-are-too-long)] | Lines are too long | 43 | 
| [[N&#x2011;09](#n09-long-functions-should-be-refactored-into-multiple-smaller-functions)] | Long functions should be refactored into multiple, smaller, functions | 1 | 
| [[N&#x2011;10](#n10-variable-names-that-consist-of-all-capital-letters-should-be-reserved-for-constantimmutable-variables)] | Variable names that consist of all capital letters should be reserved for `constant`/`immutable` variables | 1 | 
| [[N&#x2011;11](#n11-typos)] | Typos | 29 | 
| [[N&#x2011;12](#n12-natspec-param-is-missing)] | NatSpec `@param` is missing | 78 | 
| [[N&#x2011;13](#n13-natspec-return-argument-is-missing)] | NatSpec `@return` argument is missing | 21 | 
| [[N&#x2011;14](#n14-assembly-blocks-should-have-extensive-comments)] | Assembly blocks should have extensive comments | 4 | 
| [[N&#x2011;15](#n15-visibility-should-be-set-explicitly-rather-than-defaulting-to-internal)] | Visibility should be set explicitly rather than defaulting to `internal` | 3 | 
| [[N&#x2011;16](#n16-function-ordering-does-not-follow-the-solidity-style-guide)] | Function ordering does not follow the Solidity style guide | 10 | 
| [[N&#x2011;17](#n17-contract-does-not-follow-the-solidity-style-guides-suggested-layout-ordering)] | Contract does not follow the Solidity style guide's suggested layout ordering | 9 | 
| [[N&#x2011;18](#n18-interfaces-should-be-indicated-with-an-i-prefix-in-the-contract-name)] | Interfaces should be indicated with an `I` prefix in the contract name | 28 | 
| [[N&#x2011;19](#n19-add-inline-comments-for-unnamed-variables)] | Add inline comments for unnamed variables | 377 | 
| [[N&#x2011;20](#n20-top-level-declarations-should-be-separated-by-at-least-two-lines)] | Top-level declarations should be separated by at least two lines | 146 | 
| [[N&#x2011;21](#n21-consider-using-delete-rather-than-assigning-zerofalse-to-clear-values)] | Consider using `delete` rather than assigning zero/false to clear values | 11 | 
| [[N&#x2011;22](#n22-contracts-should-have-full-test-coverage)] | Contracts should have full test coverage | 1 | 
| [[N&#x2011;23](#n23-large-or-complicated-code-bases-should-implement-invariant-tests)] | Large or complicated code bases should implement invariant tests | 1 | 
| [[N&#x2011;24](#n24-consider-adding-formal-verification-proofs)] | Consider adding formal verification proofs | 1 | 
| [[N&#x2011;25](#n25-multiple-addressid-mappings-can-be-combined-into-a-single-mapping-of-an-addressid-to-a-struct-for-readability)] | Multiple `address`/ID mappings can be combined into a single `mapping` of an `address`/ID to a `struct`, for readability | 1 | 
| [[N&#x2011;26](#n26-custom-errors-should-be-used-rather-than-revertrequire)] | Custom errors should be used rather than `revert()`/`require()` | 92 | 
| [[N&#x2011;27](#n27-not-using-the-named-return-variables-anywhere-in-the-function-is-confusing)] | Not using the named return variables anywhere in the function is confusing | 20 | 
| [[N&#x2011;28](#n28-use-abiencodecall-instead-of-abiencodewithsignatureabiencodewithselector)] | Use `abi.encodeCall()` instead of `abi.encodeWithSignature()`/`abi.encodeWithSelector()` | 4 | 
| [[N&#x2011;29](#n29-function-state-mutability-can-be-restricted-to-view)] | Function state mutability can be restricted to view | 1 | 
| [[N&#x2011;30](#n30-memory-safe-annotation-preferred-over-comment-variant)] | Memory-safe annotation preferred over comment variant | 1 | 
| [[N&#x2011;31](#n31-non-externalpublic-variable-names-should-begin-with-an-underscore)] | Non-`external`/`public` variable names should begin with an underscore | 8 | 
| [[N&#x2011;32](#n32-variable-names-for-constants-dont-follow-the-solidity-style-guide)] | Variable names for `constant`s don't follow the Solidity style guide | 4 | 
| [[N&#x2011;33](#n33-variable-names-for-immutables-should-use-constant_case)] | Variable names for `immutable`s should use CONSTANT_CASE | 18 | 
| [[N&#x2011;34](#n34-array-indicies-should-be-referenced-via-enums-rather-than-via-numeric-literals)] | Array indicies should be referenced via `enum`s rather than via numeric literals | 4 | 
| [[N&#x2011;35](#n35-consider-using-named-mappings)] | Consider using named mappings | 21 | 
| [[N&#x2011;36](#n36-use-of-override-is-unnecessary)] | Use of `override` is unnecessary | 4 | 
| [[N&#x2011;37](#n37-consider-using-descriptive-constants-when-passing-zero-as-a-function-argument)] | Consider using descriptive `constant`s when passing zero as a function argument | 9 | 
| [[N&#x2011;38](#n38-variables-need-not-be-initialized-to-false)] | Variables need not be initialized to false | 1 | 
| [[N&#x2011;39](#n39-variables-need-not-be-initialized-to-zero)] | Variables need not be initialized to zero | 9 | 
| [[N&#x2011;40](#n40-consider-using-safepermit)] | Consider using `safePermit()` | 1 | 
| [[N&#x2011;41](#n41-function-state-mutability-can-be-restricted-to-pure)] | Function state mutability can be restricted to pure | 3 | 
| [[N&#x2011;42](#n42-unused-local-variable)] | Unused local variable | 1 | 
| [[N&#x2011;43](#n43-constants-should-be-defined-rather-than-using-magic-numbers)] | `constant`s should be defined rather than using magic numbers | 75 | 
| [[N&#x2011;44](#n44-consider-implementing-eip-5267-to-securely-describe-eip-712-domains-being-used)] | Consider implementing EIP-5267 to securely describe EIP-712 domains being used | 1 | 
| [[N&#x2011;45](#n45-events-are-missing-sender-information)] | Events are missing sender information | 45 | 
| [[N&#x2011;46](#n46-consider-adding-a-blockdeny-list)] | Consider adding a block/deny-list | 6 | 
| [[N&#x2011;47](#n47-unused-function-parameter)] | Unused function parameter | 4 | 
| [[N&#x2011;48](#n48-unused-event-definition)] | Unused `event` definition | 3 | 
| [[N&#x2011;49](#n49-contract-declarations-should-have-natspec-descriptions)] | Contract declarations should have NatSpec descriptions | 32 | 
| [[N&#x2011;50](#n50-modifier-declarations-should-have-natspec-descriptions)] | Modifier declarations should have NatSpec descriptions | 9 | 
| [[N&#x2011;51](#n51-event-declarations-should-have-natspec-descriptions)] | Event declarations should have NatSpec descriptions | 46 | 
| [[N&#x2011;52](#n52-state-variable-declarations-should-have-natspec-descriptions)] | State variable declarations should have NatSpec descriptions | 55 | 
| [[N&#x2011;53](#n53-function-declarations-should-have-natspec-descriptions)] | Function declarations should have NatSpec descriptions | 223 | 
| [[N&#x2011;54](#n54-function-names-should-use-lowercamelcase)] | Function names should use lowerCamelCase | 2 | 
| [[N&#x2011;55](#n55-constants-in-comparisons-should-appear-on-the-left-side)] | Constants in comparisons should appear on the left side | 57 | 
| [[N&#x2011;56](#n56-events-should-use-parameters-to-convey-information)] | Events should use parameters to convey information | 2 | 
| [[N&#x2011;57](#n57-contract-declarations-should-have-natspec-author-annotations)] | Contract declarations should have NatSpec `@author` annotations | 51 | 
| [[N&#x2011;58](#n58-contract-declarations-should-have-natspec-title-annotations)] | Contract declarations should have NatSpec `@title` annotations | 32 | 
| [[N&#x2011;59](#n59-empty-function-body)] | Empty function body | 1 | 
| [[N&#x2011;60](#n60-use-bytesconcat-on-bytes-instead-of-abiencodepacked-for-clearer-semantic-meaning)] | Use `bytes.concat()` on bytes instead of `abi.encodePacked()` for clearer semantic meaning | 1 | 
| [[N&#x2011;61](#n61-if-statement-can-be-converted-to-a-ternary)] | `if`-statement can be converted to a ternary | 4 | 
| [[N&#x2011;62](#n62-overflows-in-unchecked-blocks)] | Overflows in unchecked blocks | 1 | 
| [[N&#x2011;63](#n63-expressions-for-constant-values-should-use-immutable-rather-than-constant)] | Expressions for constant values should use `immutable` rather than `constant` | 1 | 
| [[N&#x2011;64](#n64-contract-should-expose-an-interface)] | Contract should expose an `interface` | 152 | 
| [[N&#x2011;65](#n65-missing-event-and-or-timelock-for-critical-parameter-change)] | Missing event and or timelock for critical parameter change | 1 | 
| [[N&#x2011;66](#n66-setters-should-prevent-re-setting-of-the-same-value)] | Setters should prevent re-setting of the same value | 6 | 
| [[N&#x2011;67](#n67-assembly-block-creates-dirty-bits)] | Assembly block creates dirty bits | 2 | 
| [[N&#x2011;68](#n68-polymorphic-functions-make-security-audits-more-time-consuming-and-error-prone)] | Polymorphic functions make security audits more time-consuming and error-prone | 5 | 
| [[N&#x2011;69](#n69-interfaces-should-be-defined-in-separate-files-from-their-usage)] | Interfaces should be defined in separate files from their usage | 25 | 
| [[N&#x2011;70](#n70-consider-moving-msgsender-checks-to-a-common-authorization-modifier)] | Consider moving `msg.sender` checks to a common authorization `modifier` | 1 | 
| [[N&#x2011;71](#n71-consider-disallowing-transfers-to-addressthis)] | Consider disallowing transfers to `address(this)` | 2 | 
| [[N&#x2011;72](#n72-consider-bounding-input-array-length)] | Consider bounding input array length | 4 | 
| [[N&#x2011;73](#n73-named-imports-of-parent-contracts-are-missing)] | Named imports of parent contracts are missing | 3 | 
| [[N&#x2011;74](#n74-complex-casting)] | Complex casting | 4 | 
| [[N&#x2011;75](#n75-events-may-be-emitted-out-of-order-due-to-reentrancy)] | Events may be emitted out of order due to reentrancy | 17 | 
| [[N&#x2011;76](#n76-missing-checks-constructorinitializer-assignments)] | Missing checks constructor/initializer assignments | 3 | 
| [[N&#x2011;77](#n77-missing-checks-for-state-variable-assignments)] | Missing checks for state variable assignments | 1 | 
| [[N&#x2011;78](#n78-missing-checks-for-empty-bytes-when-updating-bytes-state-variables)] | Missing checks for empty bytes when updating bytes state variables | 1 | 
| [[N&#x2011;79](#n79-state-and-local-variables-should-be-named-using-lowercamelcase)] | State and local variables should be named using lowerCamelCase | 1 | 

Total: 1992 instances over 79 issues

### Gas Optimizations

| |Issue|Instances|Total Gas Saved|
|-|:-|:-:|:-:|
| [[G&#x2011;01](#g01-enable-ir-based-code-generation)] | Enable IR-based code generation | 1 |  - |
| [[G&#x2011;02](#g02-multiple-addressid-mappings-can-be-combined-into-a-single-mapping-of-an-addressid-to-a-struct-where-appropriate)] | Multiple `address`/ID mappings can be combined into a single `mapping` of an `address`/ID to a `struct`, where appropriate | 1 |  - |
| [[G&#x2011;03](#g03-state-variables-can-be-packed-into-fewer-storage-slots-by-truncating-timestamp-bytes)] | State variables can be packed into fewer storage slots by truncating timestamp bytes | 1 |  2000 |
| [[G&#x2011;04](#g04-state-variables-should-be-cached-in-stack-variables-rather-than-re-reading-them-from-storage)] | State variables should be cached in stack variables rather than re-reading them from storage | 28 |  2716 |
| [[G&#x2011;05](#g05-multiple-accesses-of-a-mappingarray-should-use-a-local-variable-cache)] | Multiple accesses of a mapping/array should use a local variable cache | 1 |  42 |
| [[G&#x2011;06](#g06-the-result-of-function-calls-should-be-cached-rather-than-re-calling-the-function)] | The result of function calls should be cached rather than re-calling the function | 15 |  300 |
| [[G&#x2011;07](#g07-calculations-should-be-memoized-rather-than-re-calculating-them)] | Calculations should be memoized rather than re-calculating them | 10 |  200 |
| [[G&#x2011;08](#g08-internal-functions-only-called-once-can-be-inlined-to-save-gas)] | `internal` functions only called once can be inlined to save gas | 4 |  80 |
| [[G&#x2011;09](#g09-add-unchecked--for-subtractions-where-the-operands-cannot-underflow-because-of-a-previous-require-or-if-statement)] | Add `unchecked {}` for subtractions where the operands cannot underflow because of a previous `require()` or `if`-statement | 6 |  180 |
| [[G&#x2011;10](#g10-arraylength-should-not-be-looked-up-in-every-loop-of-a-for-looparray)] | `<array>.length` should not be looked up in every loop of a `for`-loop | 3 |  9 |
| [[G&#x2011;11](#g11-ii-should-be-uncheckediuncheckedi-when-it-is-not-possible-for-them-to-overflow-as-is-the-case-when-used-in-for--and-while-loops)] | `++i`/`i++` should be `unchecked{++i}`/`unchecked{i++}` when it is not possible for them to overflow, as is the case when used in `for`- and `while`-loops | 7 |  420 |
| [[G&#x2011;12](#g12-requirerevert-strings-longer-than-32-bytes-cost-extra-gas)] | `require()`/`revert()` strings longer than 32 bytes cost extra gas | 47 |  141 |
| [[G&#x2011;13](#g13-optimize-names-to-save-gas)] | Optimize names to save gas | 29 |  638 |
| [[G&#x2011;14](#g14-remove-unused-local-variable)] | Remove unused local variable | 1 |  - |
| [[G&#x2011;15](#g15-i-costs-less-gas-than-i-especially-when-its-used-in-for-loops---ii---too)] | `++i` costs less gas than `i++`, especially when it's used in `for`-loops (`--i`/`i--` too) | 9 |  45 |
| [[G&#x2011;16](#g16-usage-of-uintsints-smaller-than-32-bytes-256-bits-incurs-overhead)] | Usage of `uints`/`ints` smaller than 32 bytes (256 bits) incurs overhead | 53 |  1166 |
| [[G&#x2011;17](#g17-using-private-rather-than-public-for-constants-saves-gas)] | Using `private` rather than `public` for constants, saves gas | 11 |  - |
| [[G&#x2011;18](#g18-use-custom-errors-rather-than-revertrequire-strings-to-save-gas)] | Use custom errors rather than `revert()`/`require()` strings to save gas | 92 |  - |
| [[G&#x2011;19](#g19-functions-guaranteed-to-revert-when-called-by-normal-users-can-be-marked-payable)] | Functions guaranteed to revert when called by normal users can be marked `payable` | 80 |  1680 |
| [[G&#x2011;20](#g20-constructors-can-be-marked-payable)] | Constructors can be marked `payable` | 15 |  315 |
| [[G&#x2011;21](#g21-dont-use-_msgsender-if-not-supporting-eip-2771)] | Don't use `_msgSender()` if not supporting EIP-2771 | 22 |  352 |
| [[G&#x2011;22](#g22-using-globals-directly-is-cheaper-than-assigning-them-to-variables)] | Using globals directly is cheaper than assigning them to variables | 6 |  30 |
| [[G&#x2011;23](#g23--costs-less-gas-than-)] | `>=` costs less gas than `>` | 6 |  18 |
| [[G&#x2011;24](#g24-keccak256-should-only-need-to-be-called-on-a-specific-string-literal-once)] | `keccak256()` should only need to be called on a specific string literal once | 2 |  84 |
| [[G&#x2011;25](#g25-use-assembly-to-emit-events-in-order-to-save-gas)] | Use assembly to emit events, in order to save gas | 50 |  1900 |
| [[G&#x2011;26](#g26-splitting-require-statements-that-use--saves-gas)] | Splitting `require()` statements that use `&&` saves gas | 6 |  18 |
| [[G&#x2011;27](#g27-use--for-mappings)] | Use `+=` for `mapping`s | 1 |  40 |
| [[G&#x2011;28](#g28-using-bools-for-storage-incurs-overhead)] | Using `bool`s for storage incurs overhead | 3 |  300 |
| [[G&#x2011;29](#g29-use-uint2561uint2562-instead-of-truefalse-to-save-gas-for-changes)] | Use `uint256(1)`/`uint256(2)` instead of `true`/`false` to save gas for changes | 3 |  51300 |
| [[G&#x2011;30](#g30-simple-checks-for-zero-can-be-done-using-assembly-to-save-gas)] | Simple checks for zero can be done using assembly to save gas | 9 |  54 |
| [[G&#x2011;31](#g31-avoid-updating-storage-when-the-value-hasnt-changed)] | Avoid updating storage when the value hasn't changed | 6 |  4800 |
| [[G&#x2011;32](#g32-unchecked---can-be-used-on-the-division-of-two-uints-in-order-to-save-gas)] | `unchecked {}`  can be used on the division of two `uint`s in order to save gas | 1 |  20 |
| [[G&#x2011;33](#g33-use-assembly-for-small-keccak256-hashes-in-order-to-save-gas)] | Use assembly for small keccak256 hashes, in order to save gas | 2 |  160 |
| [[G&#x2011;34](#g34-avoid-transferring-amounts-of-zero-in-order-to-save-gas)] | Avoid transferring amounts of zero in order to save gas | 6 |  600 |
| [[G&#x2011;35](#g35-avoid-fetching-a-low-level-calls-return-data-by-using-assembly)] | Avoid fetching a low-level call's return data by using assembly | 2 |  318 |
| [[G&#x2011;36](#g36-consider-using-bytes32-rather-than-a-string)] | Consider using `bytes32` rather than a `string` | 7 |  - |

Total: 546 instances over 36 issues with **69926 gas** saved

Gas totals are estimates based on data from the Ethereum Yellowpaper. The estimates use the lower bounds of ranges and count two iterations of each `for`-loop. All values above are runtime, not deployment, values; deployment values are listed in the individual issue descriptions. The table above as well as its gas numbers do not include any of the excluded findings.

### Disputed Issues

The issues below may be reported by other bots/wardens, but can be penalized/ignored since either the rule or the specified instances are invalid

| |Issue|Instances|
|-|:-|:-:|
| [[D&#x2011;01](#d01-signatures-used-by-contract-are-vulnerable-to-malleability-attacks)] | ~~Signatures used by contract are vulnerable to malleability attacks~~ | 1 | 
| [[D&#x2011;02](#d02-unsafe-downcast)] | ~~Unsafe downcast~~ | 25 | 
| [[D&#x2011;03](#d03-array-lengths-not-checked)] | ~~Array lengths not checked~~ | 1 | 
| [[D&#x2011;04](#d04-consider-implementing-two-step-procedure-for-updating-protocol-addresses)] | ~~Consider implementing two-step procedure for updating protocol addresses~~ | 2 | 
| [[D&#x2011;05](#d05-additionmultiplication-in-unchecked-block-is-unsafe)] | ~~Addition/multiplication in `unchecked` block is unsafe~~ | 1 | 
| [[D&#x2011;06](#d06-external-call-recipient-may-consume-all-transaction-gas)] | ~~External call recipient may consume all transaction gas~~ | 8 | 
| [[D&#x2011;07](#d07-missing-checks-for-invalid-ecrecover-signature)] | ~~Missing checks for invalid `ecrecover()` signature~~ | 1 | 
| [[D&#x2011;08](#d08-abiencodepacked-should-not-be-used-with-dynamic-types-when-passing-the-result-to-a-hash-function-such-as-keccak256)] | ~~`abi.encodePacked()` should not be used with dynamic types when passing the result to a hash function such as `keccak256()`~~ | 2 | 
| [[D&#x2011;09](#d09-duplicated-requirerevert-checks-should-be-refactored-to-a-modifier-or-function-to-save-gas)] | ~~Duplicated require()/revert() checks should be refactored to a modifier Or function to save gas~~ | 12 | 
| [[D&#x2011;10](#d10-duplicated-requirerevert-checks-should-be-refactored-to-a-modifier-or-function)] | ~~Duplicated `require()`/`revert()` checks should be refactored to a modifier or function~~ | 69 | 
| [[D&#x2011;11](#d11-spdx-identifier-should-be-the-in-the-first-line-of-a-solidity-file)] | ~~SPDX identifier should be the in the first line of a solidity file~~ | 18 | 
| [[D&#x2011;12](#d12-inconsistent-comment-spacing)] | ~~Inconsistent comment spacing~~ | 3 | 
| [[D&#x2011;13](#d13-prefer-double-quotes-for-string-quoting)] | ~~Prefer double quotes for string quoting~~ | 1 | 
| [[D&#x2011;14](#d14-public-functions-not-used-internally-can-be-marked-as-external-to-save-gas)] | ~~Public functions not used internally can be marked as external to save gas~~ | 116 | 
| [[D&#x2011;15](#d15-unused-named-return-variables-without-optimizer-waste-gas)] | ~~Unused named return variables without optimizer waste gas~~ | 20 | 
| [[D&#x2011;16](#d16-event-names-should-use-camelcase)] | ~~Event names should use CamelCase~~ | 46 | 
| [[D&#x2011;17](#d17-usage-of-intsuints-smaller-than-32-bytes-incurs-overhead)] | ~~Usage of ints/uints smaller than 32 bytes incurs overhead~~ | 2 | 
| [[D&#x2011;18](#d18-unnecessary-look-up-in-if-condition)] | ~~Unnecessary look up in if condition~~ | 4 | 
| [[D&#x2011;19](#d19-timestamp-may-be-manipulation)] | ~~Timestamp may be manipulation~~ | 9 | 
| [[D&#x2011;20](#d20-revert-on-transfer-to-the-zero-address)] | ~~Revert on transfer to the zero address~~ | 2 | 
| [[D&#x2011;21](#d21-using-bitmap-to-store-bool-states-can-save-gas)] | ~~Using bitmap to store bool states can save gas~~ | 3 | 
| [[D&#x2011;22](#d22-all-interfaces-used-within-a-project-should-be-imported)] | ~~All interfaces used within a project should be imported~~ | 33 | 
| [[D&#x2011;23](#d23-its-not-standard-to-end-and-begin-a-code-object-on-the-same-line)] | ~~It's not standard to end and begin a code object on the same line~~ | 34 | 
| [[D&#x2011;24](#d24-use-assembly-to-write-addresscontract-type-storage-values)] | ~~Use `assembly` to write address/contract type storage values~~ | 15 | 
| [[D&#x2011;25](#d25-use-multiple-require-and-if-statements-instead-of-)] | ~~Use multiple `require()` and `if` statements instead of `&&`~~ | 1 | 
| [[D&#x2011;26](#d26-nesting-if-statements-is-cheaper-than-using-)] | ~~Nesting `if`-statements is cheaper than using `&&`~~ | 1 | 
| [[D&#x2011;27](#d27-it-is-standard-for-all-external-and-public-functions-to-be-override-from-an-interface)] | ~~It is standard for all external and public functions to be override from an interface~~ | 4 | 
| [[D&#x2011;28](#d28-must-approve-or-increase-allowance-first)] | ~~Must approve or increase allowance first~~ | 9 | 
| [[D&#x2011;29](#d29-cast-to-bytes-or-bytes32-for-clearer-semantic-meaning)] | ~~Cast to `bytes` or `bytes32` for clearer semantic meaning~~ | 28 | 
| [[D&#x2011;30](#d30-unsafe-erc20-operations)] | ~~Unsafe ERC20 operation(s)~~ | 11 | 
| [[D&#x2011;31](#d31-functions-calling-contractsaddresses-with-transfer-hooks-are-missing-reentrancy-guards)] | ~~Functions calling contracts/addresses with transfer hooks are missing reentrancy guards~~ | 6 | 
| [[D&#x2011;32](#d32-return-values-of-transfertransferfrom-not-checked)] | ~~Return values of transfer()/transferFrom() not checked~~ | 6 | 
| [[D&#x2011;33](#d33-some-tokens-may-revert-when-zero-value-transfers-are-made)] | ~~Some tokens may revert when zero value transfers are made~~ | 6 | 
| [[D&#x2011;34](#d34-return-values-of-approve-not-checked)] | ~~Return values of `approve()` not checked~~ | 5 | 
| [[D&#x2011;35](#d35-array-lengths-not-checked)] | ~~Array lengths not checked~~ | 4 | 
| [[D&#x2011;36](#d36-safetransfer-should-be-used-in-place-of-transfer)] | ~~SafeTransfer should be used in place of transfer~~ | 2 | 
| [[D&#x2011;37](#d37-use-bytesconcat-on-bytes-instead-of-abiencodepacked-for-clearer-semantic-meaning)] | ~~Use `bytes.concat()` on bytes instead of `abi.encodePacked()` for clearer semantic meaning~~ | 27 | 
| [[D&#x2011;38](#d38-use-inheritdoc-rather-than-using-a-non-standard-annotation)] | ~~Use `@inheritdoc` rather than using a non-standard annotation~~ | 1 | 
| [[D&#x2011;39](#d39-empty-function-body)] | ~~Empty function body~~ | 1 | 
| [[D&#x2011;40](#d40-operator--costs-more-gas-than---for-state-variables)] | ~~Operator += costs more gas than = + for state variables~~ | 4 | 
| [[D&#x2011;41](#d41-contract-should-expose-an-interface)] | ~~Contract should expose an `interface`~~ | 2 | 
| [[D&#x2011;42](#d42-storage-write-removal-bug-on-conditional-early-termination)] | ~~Storage Write Removal Bug On Conditional Early Termination~~ | 4 | 
| [[D&#x2011;43](#d43-functions-which-are-either-private-or-internal-should-have-a-preceding-_-in-their-name)] | ~~Functions which are either private or internal should have a preceding _ in their name~~ | 77 | 
| [[D&#x2011;44](#d44-low-level-calls-with-solidity-before-0814-result-in-an-optimiser-bug)] | ~~Low level calls with Solidity before 0.8.14 result in an optimiser bug~~ | 4 | 
| [[D&#x2011;45](#d45-abiencode-is-less-efficient-than-abiencodepacked)] | ~~`abi.encode()` is less efficient than `abi.encodepacked()`~~ | 2 | 
| [[D&#x2011;46](#d46-large-approvals-may-not-work-with-some-erc20-tokens)] | ~~Large approvals may not work with some ERC20 tokens~~ | 6 | 
| [[D&#x2011;47](#d47-not-initializing-local-variables-to-zero-saves-gas)] | ~~Not initializing local variables to zero saves gas~~ | 8 | 
| [[D&#x2011;48](#d48-splitting-require-statements-that-use--saves-gas)] | ~~Splitting `require()` statements that use `&&` saves gas~~ | 4 | 
| [[D&#x2011;49](#d49-using-storage-instead-of-memory-for-structsarrays-saves-gas)] | ~~Using `storage` instead of `memory` for structs/arrays saves gas~~ | 3 | 
| [[D&#x2011;50](#d50-use-assembly-to-emit-events-in-order-to-save-gas)] | ~~Use assembly to emit events, in order to save gas~~ | 2 | 
| [[D&#x2011;51](#d51-events-that-mark-critical-parameter-changes-should-contain-both-the-old-and-the-new-value)] | ~~Events that mark critical parameter changes should contain both the old and the new value~~ | 59 | 
| [[D&#x2011;52](#d52-i-costs-less-gas-than-i-especially-when-its-used-in-for-loops---ii---too)] | ~~`++i` costs less gas than `i++`, especially when it's used in `for`-loops (`--i`/`i--` too)~~ | 1 | 
| [[D&#x2011;53](#d53-function-names-not-in-mixedcase)] | ~~Function Names Not in mixedCase~~ | 19 | 
| [[D&#x2011;54](#d54-bad-bot-rules)] | ~~Bad bot rules~~ | 1 | 
| [[D&#x2011;55](#d55-do-not-use-underscore-at-the-end-of-variable-name)] | ~~Do not use underscore at the end of variable name~~ | 18 | 
| [[D&#x2011;56](#d56-contracts-do-not-work-with-fee-on-transfer-tokens)] | ~~Contracts do not work with fee-on-transfer tokens~~ | 4 | 
| [[D&#x2011;57](#d57-re-org-attack)] | ~~Re-org attack~~ | 3 | 
| [[D&#x2011;58](#d58-safetransfer-function-does-not-check-for-contract-existence)] | ~~`safeTransfer` function does not check for contract existence~~ | 2 | 
| [[D&#x2011;59](#d59-safetransferlib-does-not-ensure-that-the-token-contract-exists)] | ~~`SafeTransferLib` does not ensure that the token contract exists~~ | 2 | 
| [[D&#x2011;60](#d60-default-bool-values-are-manually-reset)] | ~~Default `bool` values are manually reset~~ | 8 | 
| [[D&#x2011;61](#d61-interfaces-should-be-defined-in-separate-files-from-their-usage)] | ~~Interfaces should be defined in separate files from their usage~~ | 7 | 
| [[D&#x2011;62](#d62-using-calldata-instead-of-memory-for-read-only-arguments-in-external-functions-saves-gas)] | ~~Using `calldata` instead of `memory` for read-only arguments in `external` functions saves gas~~ | 1 | 
| [[D&#x2011;63](#d63-unusual-loop-variable)] | ~~Unusual loop variable~~ | 6 | 
| [[D&#x2011;64](#d64-use-delete-instead-of-setting-mappingstate-variable-to-zero-to-save-gas)] | ~~Use delete instead of setting mapping/state variable to zero, to save gas~~ | 9 | 
| [[D&#x2011;65](#d65-shorten-the-array-rather-than-copying-to-a-new-one)] | ~~Shorten the array rather than copying to a new one~~ | 3 | 
| [[D&#x2011;66](#d66-avoid-fetching-a-low-level-calls-return-data-by-using-assembly)] | ~~Avoid fetching a low-level call's return data by using assembly~~ | 8 | 
| [[D&#x2011;67](#d67-change-public-function-visibility-to-external-to-save-gas)] | ~~Change `public` function visibility to `external` to save gas~~ | 108 | 
| [[D&#x2011;68](#d68-a-function-which-defines-named-returns-in-its-declaration-doesnt-need-to-use-return)] | ~~A function which defines named returns in its declaration doesn't need to use return~~ | 9 | 
| [[D&#x2011;69](#d69-not-using-the-named-return-variables-anywhere-in-the-function-is-confusing)] | ~~Not using the named return variables anywhere in the function is confusing~~ | 2 | 
| [[D&#x2011;70](#d70-state-variables-not-capped-at-reasonable-values)] | ~~State variables not capped at reasonable values~~ | 5 | 
| [[D&#x2011;71](#d71-unused-import)] | ~~Unused import~~ | 36 | 
| [[D&#x2011;72](#d72-safemint-should-be-used-in-place-of-mint)] | ~~safeMint should be used in place of mint~~ | 3 | 
| [[D&#x2011;73](#d73-unused-struct-definition)] | ~~Unused `struct` definition~~ | 3 | 
| [[D&#x2011;74](#d74-change-public-to-external-for-functions-that-are-not-called-internally)] | ~~Change `public` to `external` for functions that are not called internally~~ | 2 | 
| [[D&#x2011;75](#d75-internal-functions-not-called-by-the-contract-should-be-removed)] | ~~`internal` functions not called by the contract should be removed~~ | 82 | 

Total: 1057 instances over 75 issues





## Medium Risk Issues


### [M&#x2011;01] Contracts are vulnerable to rebasing accounting-related issues
Rebasing tokens are tokens that have each holder's `balanceof()` increase over time. Aave aTokens are an example of such tokens. If rebasing tokens are used, rewards accrue to the contract holding the tokens, and cannot be withdrawn by the original depositor. To address the issue, track 'shares' deposited on a pro-rata basis, and let shares be redeemed for their proportion of the current balance at the time of the withdrawal.

*There is one instance of this issue:*

```solidity
File: src/PoolManager.sol

128      function transfer(address currencyAddress, bytes32 recipient, uint128 amount) public {
129          uint128 currency = currencyAddressToId[currencyAddress];
130          require(currency != 0, "PoolManager/unknown-currency");
131  
132          SafeTransferLib.safeTransferFrom(currencyAddress, msg.sender, address(escrow), amount);
133          gateway.transfer(currency, msg.sender, recipient, amount);
134:     }

```
*GitHub*: [128](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L128-L134)

## Low Risk Issues


### [L&#x2011;01] Loss of precision
Division by large numbers may result in the result being zero, due to solidity not supporting fractions. Consider requiring a minimum amount for the numerator to ensure that it is always larger than the denominator

*There is one instance of this issue:*

```solidity
File: src/InvestmentManager.sol

692:          value = _toUint128(_value / 10 ** (PRICE_DECIMALS - decimals));

```
*GitHub*: [692](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L692)


### [L&#x2011;02] `safeApprove()` is deprecated
[Deprecated](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/bfff03c0d2a59bcd8e2ead1da9aed9edf0080d05/contracts/token/ERC20/utils/SafeERC20.sol#L38-L45) in favor of `safeIncreaseAllowance()` and `safeDecreaseAllowance()`. If only setting the initial allowance to the value that means infinite, `safeIncreaseAllowance()` can be used instead. The function may currently work, but if a bug is found in this version of OpenZeppelin, and the version that you're forced to upgrade to no longer has this function, you'll encounter unnecessary delays in porting and testing replacement contracts.

*There is one instance of this issue:*

```solidity
File: src/Escrow.sol

24:           SafeTransferLib.safeApprove(token, spender, value);

```
*GitHub*: [24](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L24)


### [L&#x2011;03] External calls in an un-bounded `for-`loop may result in a DOS
Consider limiting the number of iterations in `for-`loops that make external calls

*There are 3 instances of this issue:*

```solidity
File: src/util/Factory.sol

48:              liquidityPool.rely(wards[i]);

104:             token.rely(trancheTokenWards[i]);

118:             restrictionManager.rely(restrictionManagerWards[i]);

```
*GitHub*: [48](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L48-L48), [104](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L104-L104), [118](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L118-L118)


### [L&#x2011;04] Consider implementing two-step procedure for updating protocol addresses
A copy-paste error or a typo may end up bricking protocol functionality, or sending tokens to an address with no known private key. Consider implementing a two-step procedure for updating protocol addresses, where the recipient is set as pending, and must 'accept' the assignment by making an affirmative call. A straight forward way of doing this would be to have the target contracts implement [EIP-165](https://eips.ethereum.org/EIPS/eip-165), and to have the 'set' functions ensure that the recipient is of the right interface type.

*There is one instance of this issue:*

```solidity
File: src/gateway/Gateway.sol

147      function updateOutgoingRouter(address router) public auth {
148          outgoingRouter = RouterLike(router);
149          emit UpdateOutgoingRouter(router);
150:     }

```
*GitHub*: [147](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L147-L150)


### [L&#x2011;05] `decimals()` is not a part of the ERC-20 standard
The `decimals()` function is not a part of the [ERC-20 standard](https://eips.ethereum.org/EIPS/eip-20), and was added later as an [optional extension](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/extensions/IERC20Metadata.sol). As such, some valid ERC20 tokens do not support this interface, so it is unsafe to blindly cast all tokens to this interface, and then call this function.

*There are 2 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

701:         currencyDecimals = ERC20Like(LiquidityPoolLike(liquidityPool).asset()).decimals();

```
*GitHub*: [701](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L701-L701)

```solidity
File: src/PoolManager.sol

243:         require(IERC20(currencyAddress).decimals() <= MAX_CURRENCY_DECIMALS, "PoolManager/too-many-currency-decimals");

```
*GitHub*: [243](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L243-L243)


### [L&#x2011;06] Missing checks for `ecrecover()` signature malleability
`ecrecover()` accepts as valid, two versions of signatures, meaning an attacker can use the same signature twice, or an attacker may be able to front-run the original signer with the altered version of the signature, causing the signer's transaction to revert due to nonce reuse. Consider adding checks for signature malleability, or using OpenZeppelin's `ECDSA` library to perform the extra checks necessary in order to prevent malleability.

*There is one instance of this issue:*

```solidity
File: src/token/ERC20.sol

206:             if (signer == ecrecover(digest, v, r, s)) {

```
*GitHub*: [206](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L206-L206)


### [L&#x2011;07] Missing contract-existence checks before low-level calls
Low-level calls return success if there is no code present at the specified address. In addition to the zero-address checks, add a check to verify that `<address>.code.length > 0`

*There are 9 instances of this issue:*

```solidity
File: src/LiquidityPool.sol

296          (bool success, bytes memory data) = address(share).call(bytes.concat(msg.data, bytes20(msg.sender)));
297          _successCheck(success);
298          return abi.decode(data, (bool));
299:     }

302          (bool success, bytes memory data) = address(share).call(bytes.concat(msg.data, bytes20(msg.sender)));
303          _successCheck(success);
304          return abi.decode(data, (bool));
305:     }

308          (bool success, bytes memory data) = address(share).call(bytes.concat(msg.data, bytes20(msg.sender)));
309          _successCheck(success);
310          return abi.decode(data, (bool));
311:     }

314          (bool success,) = address(share).call(bytes.concat(msg.data, bytes20(address(this))));
315          _successCheck(success);
316:     }

319          (bool success,) = address(share).call(bytes.concat(msg.data, bytes20(address(this))));
320          _successCheck(success);
321:     }

```
*GitHub*: [296](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L296-L299), [302](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L302-L305), [308](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L308-L311), [314](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L314-L316), [319](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L319-L321)

```solidity
File: src/token/ERC20.sol

212              signer.staticcall(abi.encodeWithSelector(IERC1271.isValidSignature.selector, digest, signature));
213          return (success && result.length == 32 && abi.decode(result, (bytes4)) == IERC1271.isValidSignature.selector);
214:     }

```
*GitHub*: [212](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L212-L214)

```solidity
File: src/util/SafeTransferLib.sol

17               token.call(abi.encodeWithSelector(IERC20.transferFrom.selector, from, to, value));
18           require(success && (data.length == 0 || abi.decode(data, (bool))), "SafeTransferLib/safe-transfer-from-failed");
19:      }

27           (bool success, bytes memory data) = token.call(abi.encodeWithSelector(IERC20.transfer.selector, to, value));
28           require(success && (data.length == 0 || abi.decode(data, (bool))), "SafeTransferLib/safe-transfer-failed");
29:      }

37           (bool success, bytes memory data) = token.call(abi.encodeWithSelector(IERC20.approve.selector, to, value));
38           require(success && (data.length == 0 || abi.decode(data, (bool))), "SafeTransferLib/safe-approve-failed");
39:      }

```
*GitHub*: [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L17-L19), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L27-L29), [37](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L37-L39)


### [L&#x2011;08] Code does not follow the best practice of check-effects-interaction
Code should follow the best-practice of [check-effects-interaction](https://blockchain-academy.hs-mittweida.de/courses/solidity-coding-beginners-to-intermediate/lessons/solidity-11-coding-patterns/topic/checks-effects-interactions/), where state variables are updated before any external calls are made. Doing so prevents a large class of reentrancy bugs.

*There are 5 instances of this issue:*

```solidity
File: src/PoolManager.sol

/// @audit approve() called prior to this assignment
245:         currencyIdToAddress[currency] = currencyAddress;

/// @audit approve() called prior to this assignment
246:         currencyAddressToId[currencyAddress] = currency;

/// @audit newTrancheToken() called prior to this assignment
302:         tranche.token = token;

/// @audit newLiquidityPool() called prior to this assignment
322:         tranche.liquidityPools[currency] = liquidityPool;

```
*GitHub*: [245](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L245-L245), [246](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L246-L246), [302](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L302-L302), [322](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L322-L322)

```solidity
File: src/UserEscrow.sol

/// @audit null() called prior to this assignment
46:          destinations[token][destination] -= amount;

```
*GitHub*: [46](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L46-L46)


### [L&#x2011;09] Missing checks for `address(0x0)` in the constructor/initializer


*There are 18 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

89:          escrow = EscrowLike(escrow_);

90:          userEscrow = UserEscrowLike(userEscrow_);

```
*GitHub*: [89](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L89-L89), [90](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L90-L90)

```solidity
File: src/LiquidityPool.sol

88:          asset = asset_;

89:          share = TrancheTokenLike(share_);

90:          investmentManager = InvestmentManagerLike(investmentManager_);

```
*GitHub*: [88](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L88-L88), [89](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L89-L89), [90](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L90-L90)

```solidity
File: src/PoolManager.sol

105:         escrow = EscrowLike(escrow_);

106:         liquidityPoolFactory = LiquidityPoolFactoryLike(liquidityPoolFactory_);

107:         trancheTokenFactory = TrancheTokenFactoryLike(trancheTokenFactory_);

```
*GitHub*: [105](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L105-L105), [106](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L106-L106), [107](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L107-L107)

```solidity
File: src/Root.sol

35:          escrow = _escrow;

```
*GitHub*: [35](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L35-L35)

```solidity
File: src/admins/DelayedAdmin.sol

19:          root = Root(root_);

```
*GitHub*: [19](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L19-L19)

```solidity
File: src/admins/PauseAdmin.sol

22:          root = Root(root_);

```
*GitHub*: [22](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L22-L22)

```solidity
File: src/gateway/Gateway.sol

99:          root = RootLike(root_);

100:         investmentManager = InvestmentManagerLike(investmentManager_);

101:         poolManager = PoolManagerLike(poolManager_);

103:         outgoingRouter = RouterLike(router_);

```
*GitHub*: [99](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L99-L99), [100](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L100-L100), [101](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L101-L101), [103](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L103-L103)

```solidity
File: src/gateway/routers/axelar/Router.sol

37:          axelarGateway = AxelarGatewayLike(axelarGateway_);

```
*GitHub*: [37](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L37-L37)

```solidity
File: src/util/Factory.sol

30:          root = _root;

75:          root = _root;

```
*GitHub*: [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L30-L30), [75](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L75-L75)

</details>




### [L&#x2011;10] Missing checks for `address(0x0)` when updating `address` state variables


*There are 7 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

105:         else if (what == "poolManager") poolManager = PoolManagerLike(data);

```
*GitHub*: [105](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L105-L105)

```solidity
File: src/LiquidityPool.sol

104:         if (what == "investmentManager") investmentManager = InvestmentManagerLike(data);

```
*GitHub*: [104](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L104-L104)

```solidity
File: src/PoolManager.sol

122:         else if (what == "investmentManager") investmentManager = InvestmentManagerLike(data);

```
*GitHub*: [122](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L122-L122)

```solidity
File: src/gateway/Gateway.sol

132:         else if (what == "investmentManager") investmentManager = InvestmentManagerLike(data);

148:         outgoingRouter = RouterLike(router);

```
*GitHub*: [132](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L132-L132), [148](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L148-L148)

```solidity
File: src/gateway/routers/axelar/Router.sol

64:              gateway = GatewayLike(data);

```
*GitHub*: [64](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L64-L64)

```solidity
File: src/token/Tranche.sol

43:          if (what == "restrictionManager") restrictionManager = ERC1404Like(data);

```
*GitHub*: [43](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L43-L43)


### [L&#x2011;11] State variables not capped at reasonable values
Consider adding minimum/maximum value checks to ensure that the state variables below can never be used to excessively harm users, including via griefing

*There is one instance of this issue:*

```solidity
File: src/LiquidityPool.sol

325:         latestPrice = price;

```
*GitHub*: [325](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L325-L325)

## Non-critical Issues


### [N&#x2011;01] `public` functions not called by the contract should be declared `external` instead
Contracts [are allowed](https://docs.soliditylang.org/en/latest/contracts.html#function-overriding) to override their parents' functions and change the visibility from `external` to `public`.

*There are 116 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

117:      function requestDeposit(uint256 currencyAmount, address user) public auth {

148:      function requestRedeem(uint256 trancheTokenAmount, address user) public auth {

174:      function decreaseDepositRequest(uint256 _currencyAmount, address user) public auth {

187:      function decreaseRedeemRequest(uint256 _trancheTokenAmount, address user) public auth {

200:      function collectDeposit(address user) public auth {

211:      function collectRedeem(address user) public auth {

223       function updateTrancheTokenPrice(uint64 poolId, bytes16 trancheId, uint128 currencyId, uint128 price)
224           public
225:          onlyGateway

234       function handleExecutedCollectInvest(
235           uint64 poolId,
236           bytes16 trancheId,
237           address recipient,
238           uint128 currency,
239           uint128 currencyPayout,
240           uint128 trancheTokensPayout
241:      ) public onlyGateway {

255       function handleExecutedCollectRedeem(
256           uint64 poolId,
257           bytes16 trancheId,
258           address recipient,
259           uint128 currency,
260           uint128 currencyPayout,
261           uint128 trancheTokensPayout
262:      ) public onlyGateway {

277       function handleExecutedDecreaseInvestOrder(
278           uint64 poolId,
279           bytes16 trancheId,
280           address user,
281           uint128 currency,
282           uint128 currencyPayout
283:      ) public onlyGateway {

294       function handleExecutedDecreaseRedeemOrder(
295           uint64 poolId,
296           bytes16 trancheId,
297           address user,
298           uint128 currency,
299           uint128 trancheTokenPayout
300:      ) public onlyGateway {

319:      function totalAssets(uint256 totalSupply, address liquidityPool) public view returns (uint256 _totalAssets) {

325:      function convertToShares(uint256 _assets, address liquidityPool) public view auth returns (uint256 shares) {

350:      function maxDeposit(address user, address liquidityPool) public view returns (uint256 currencyAmount) {

355:      function maxMint(address user, address liquidityPool) public view returns (uint256 trancheTokenAmount) {

360:      function maxWithdraw(address user, address liquidityPool) public view returns (uint256 currencyAmount) {

365:      function maxRedeem(address user, address liquidityPool) public view returns (uint256 trancheTokenAmount) {

370       function previewDeposit(address user, address liquidityPool, uint256 _currencyAmount)
371           public
372           view
373:          returns (uint256 trancheTokenAmount)

383       function previewMint(address user, address liquidityPool, uint256 _trancheTokenAmount)
384           public
385           view
386:          returns (uint256 currencyAmount)

396       function previewWithdraw(address user, address liquidityPool, uint256 _currencyAmount)
397           public
398           view
399:          returns (uint256 trancheTokenAmount)

409       function previewRedeem(address user, address liquidityPool, uint256 _trancheTokenAmount)
410           public
411           view
412:          returns (uint256 currencyAmount)

427:      function processDeposit(address user, uint256 currencyAmount) public auth returns (uint256 trancheTokenAmount) {

451:      function processMint(address user, uint256 trancheTokenAmount) public auth returns (uint256 currencyAmount) {

489       function processRedeem(uint256 trancheTokenAmount, address receiver, address user)
490           public
491           auth
492:          returns (uint256 currencyAmount)

515       function processWithdraw(uint256 currencyAmount, address receiver, address user)
516           public
517           auth
518:          returns (uint256 trancheTokenAmount)

```
*GitHub*: [117](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L117), [148](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L148), [174](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L174), [187](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L187), [200](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L200), [211](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L211), [223](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L223-L225), [234](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L234-L241), [255](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L255-L262), [277](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L277-L283), [294](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L294-L300), [319](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L319), [325](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L325), [350](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L350), [355](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L355), [360](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L360), [365](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L365), [370](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L370-L373), [383](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L383-L386), [396](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L396-L399), [409](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L409-L412), [427](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L427), [451](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L451), [489](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L489-L492), [515](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L515-L518)

```solidity
File: src/LiquidityPool.sol

103:      function file(bytes32 what, address data) public auth {

111:      function totalAssets() public view returns (uint256) {

118:      function convertToShares(uint256 assets) public view returns (uint256 shares) {

125:      function convertToAssets(uint256 shares) public view returns (uint256 assets) {

130:      function maxDeposit(address receiver) public view returns (uint256) {

135:      function previewDeposit(uint256 assets) public view returns (uint256 shares) {

141:      function deposit(uint256 assets, address receiver) public returns (uint256 shares) {

148:      function mint(uint256 shares, address receiver) public returns (uint256 assets) {

165:      function maxWithdraw(address receiver) public view returns (uint256 maxAssets) {

170:      function previewWithdraw(uint256 assets) public view returns (uint256 shares) {

176       function withdraw(uint256 assets, address receiver, address owner)
177           public
178           withApproval(owner)
179:          returns (uint256 shares)

187:      function maxRedeem(address owner) public view returns (uint256 maxShares) {

192:      function previewRedeem(uint256 shares) public view returns (uint256 assets) {

200       function redeem(uint256 shares, address receiver, address owner)
201           public
202           withApproval(owner)
203:          returns (uint256 assets)

214:      function requestDeposit(uint256 assets, address owner) public withApproval(owner) {

220:      function requestDepositWithPermit(uint256 assets, address owner, uint256 deadline, uint8 v, bytes32 r, bytes32 s)

231:      function requestRedeem(uint256 shares, address owner) public withApproval(owner) {

237:      function requestRedeemWithPermit(uint256 shares, address owner, uint256 deadline, uint8 v, bytes32 r, bytes32 s)

247:      function decreaseDepositRequest(uint256 assets, address owner) public withApproval(owner) {

253:      function decreaseRedeemRequest(uint256 shares, address owner) public withApproval(owner) {

259:      function collectDeposit(address receiver) public {

265:      function collectRedeem(address receiver) public {

271:      function name() public view returns (string memory) {

275:      function symbol() public view returns (string memory) {

279:      function decimals() public view returns (uint8) {

287:      function balanceOf(address owner) public view returns (uint256) {

291:      function allowance(address owner, address spender) public view returns (uint256) {

295:      function transferFrom(address, address, uint256) public returns (bool) {

301:      function transfer(address, uint256) public returns (bool) {

307:      function approve(address, uint256) public returns (bool) {

313:      function mint(address, uint256) public auth {

318:      function burn(address, uint256) public auth {

324:      function updatePrice(uint128 price) public auth {

332:      function checkTransferRestriction(address from, address to, uint256 value) public view returns (bool) {

```
*GitHub*: [103](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L103), [111](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L111), [118](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L118), [125](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L125), [130](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L130), [135](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L135), [141](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L141), [148](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L148), [165](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L165), [170](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L170), [176](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L176-L179), [187](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L187), [192](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L192), [200](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L200-L203), [214](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L214), [220](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L220), [231](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L231), [237](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L237), [247](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L247), [253](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L253), [259](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L259), [265](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L265), [271](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L271), [275](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L275), [279](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L279), [287](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L287), [291](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L291), [295](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L295), [301](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L301), [307](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L307), [313](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L313), [318](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L318), [324](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L324), [332](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L332)

```solidity
File: src/PoolManager.sol

128:      function transfer(address currencyAddress, bytes32 recipient, uint128 amount) public {

136       function transferTrancheTokensToCentrifuge(
137           uint64 poolId,
138           bytes16 trancheId,
139           bytes32 destinationAddress,
140:          uint128 amount

149       function transferTrancheTokensToEVM(
150           uint64 poolId,
151           bytes16 trancheId,
152           uint64 destinationChainId,
153           address destinationAddress,
154:          uint128 amount

168:      function addPool(uint64 poolId) public onlyGateway {

179:      function allowPoolCurrency(uint64 poolId, uint128 currency) public onlyGateway {

192       function addTranche(
193           uint64 poolId,
194           bytes16 trancheId,
195           string memory tokenName,
196           string memory tokenSymbol,
197           uint8 decimals
198:      ) public onlyGateway {

214       function updateTrancheTokenMetadata(
215           uint64 poolId,
216           bytes16 trancheId,
217           string memory tokenName,
218           string memory tokenSymbol
219:      ) public onlyGateway {

227:      function updateMember(uint64 poolId, bytes16 trancheId, address user, uint64 validUntil) public onlyGateway {

238:      function addCurrency(uint128 currency, address currencyAddress) public onlyGateway {

257:      function handleTransfer(uint128 currency, address recipient, uint128 amount) public onlyGateway {

265       function handleTransferTrancheTokens(uint64 poolId, bytes16 trancheId, address destinationAddress, uint128 amount)
266           public
267:          onlyGateway

280:      function deployTranche(uint64 poolId, bytes16 trancheId) public returns (address) {

307:      function deployLiquidityPool(uint64 poolId, bytes16 trancheId, address currency) public returns (address) {

341:      function getLiquidityPool(uint64 poolId, bytes16 trancheId, address currency) public view returns (address) {

```
*GitHub*: [128](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L128), [136](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L136-L140), [149](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L149-L154), [168](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L168), [179](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L179), [192](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L192-L198), [214](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L214-L219), [227](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L227), [238](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L238), [257](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L257), [265](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L265-L267), [280](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L280), [307](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L307), [341](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L341)

```solidity
File: src/Root.sol

75:       function executeScheduledRely(address target) public {

90:       function relyContract(address target, address user) public auth {

98:       function denyContract(address target, address user) public auth {

```
*GitHub*: [75](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L75), [90](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L90), [98](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L98)

```solidity
File: src/admins/DelayedAdmin.sol

26:       function pause() public auth {

30:       function unpause() public auth {

34:       function scheduleRely(address target) public auth {

38:       function cancelRely(address target) public auth {

```
*GitHub*: [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L26), [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L30), [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L34), [38](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L38)

```solidity
File: src/admins/PauseAdmin.sol

45:       function pause() public canPause {

```
*GitHub*: [45](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L45)

```solidity
File: src/gateway/Gateway.sol

130:      function file(bytes32 what, address data) public auth {

137:      function addIncomingRouter(address router) public auth {

142:      function removeIncomingRouter(address router) public auth {

147:      function updateOutgoingRouter(address router) public auth {

153       function transferTrancheTokensToCentrifuge(
154           uint64 poolId,
155           bytes16 trancheId,
156           address sender,
157           bytes32 destinationAddress,
158           uint128 amount
159:      ) public onlyPoolManager pauseable {

172       function transferTrancheTokensToEVM(
173           uint64 poolId,
174           bytes16 trancheId,
175           address sender,
176           uint64 destinationChainId,
177           address destinationAddress,
178           uint128 amount
179:      ) public onlyPoolManager pauseable {

192       function transfer(uint128 token, address sender, bytes32 receiver, uint128 amount)
193           public
194           onlyPoolManager
195:          pauseable

200       function increaseInvestOrder(
201           uint64 poolId,
202           bytes16 trancheId,
203           address investor,
204           uint128 currency,
205           uint128 currencyAmount
206:      ) public onlyInvestmentManager pauseable {

212       function decreaseInvestOrder(
213           uint64 poolId,
214           bytes16 trancheId,
215           address investor,
216           uint128 currency,
217           uint128 currencyAmount
218:      ) public onlyInvestmentManager pauseable {

224       function increaseRedeemOrder(
225           uint64 poolId,
226           bytes16 trancheId,
227           address investor,
228           uint128 currency,
229           uint128 trancheTokenAmount
230:      ) public onlyInvestmentManager pauseable {

238       function decreaseRedeemOrder(
239           uint64 poolId,
240           bytes16 trancheId,
241           address investor,
242           uint128 currency,
243           uint128 trancheTokenAmount
244:      ) public onlyInvestmentManager pauseable {

252       function collectInvest(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)
253           public
254           onlyInvestmentManager
255:          pauseable

260       function collectRedeem(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)
261           public
262           onlyInvestmentManager
263:          pauseable

268       function cancelInvestOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)
269           public
270           onlyInvestmentManager
271:          pauseable

276       function cancelRedeemOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)
277           public
278           onlyInvestmentManager
279:          pauseable

```
*GitHub*: [130](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L130), [137](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L137), [142](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L142), [147](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L147), [153](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L153-L159), [172](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L172-L179), [192](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L192-L195), [200](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L200-L206), [212](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L212-L218), [224](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L224-L230), [238](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L238-L244), [252](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L252-L255), [260](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L260-L263), [268](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L268-L271), [276](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L276-L279)

```solidity
File: src/gateway/Messages.sol

836:      function formatDomain(Domain domain) public pure returns (bytes9) {

840:      function formatDomain(Domain domain, uint64 chainId) public pure returns (bytes9) {

```
*GitHub*: [836](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L836), [840](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L840)

```solidity
File: src/gateway/routers/axelar/Router.sol

73        function execute(
74            bytes32 commandId,
75            string calldata sourceChain,
76            string calldata sourceAddress,
77            bytes calldata payload
78:       ) public onlyCentrifugeChainOrigin(sourceChain, sourceAddress) {

89:       function send(bytes calldata message) public onlyGateway {

```
*GitHub*: [73](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L73-L78), [89](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L89)

```solidity
File: src/token/ERC20.sol

91:       function transfer(address to, uint256 value) public virtual returns (bool) {

106:      function transferFrom(address from, address to, uint256 value) public virtual returns (bool) {

162:      function mint(address to, uint256 value) public virtual auth {

```
*GitHub*: [91](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L91), [106](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L106), [162](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L162)

```solidity
File: src/token/RestrictionManager.sol

28:       function detectTransferRestriction(address from, address to, uint256 value) public view returns (uint8) {

36:       function messageForTransferRestriction(uint8 restrictionCode) public view returns (string memory) {

45:       function member(address user) public view {

62:       function updateMembers(address[] memory users, uint256 validUntil) public auth {

```
*GitHub*: [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L28), [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L36), [45](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L45), [62](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L62)

```solidity
File: src/token/Tranche.sol

42:       function file(bytes32 what, address data) public auth {

48:       function addLiquidityPool(address liquidityPool) public auth {

53:       function removeLiquidityPool(address liquidityPool) public auth {

59:       function transfer(address to, uint256 value) public override restricted(_msgSender(), to, value) returns (bool) {

63        function transferFrom(address from, address to, uint256 value)
64            public
65            override
66            restricted(from, to, value)
67:           returns (bool)

72:       function mint(address to, uint256 value) public override restricted(_msgSender(), to, value) {

80:       function checkTransferRestriction(address from, address to, uint256 value) public view returns (bool) {

```
*GitHub*: [42](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L42), [48](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L48), [53](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L53), [59](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L59), [63](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L63-L67), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L72), [80](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L80)

```solidity
File: src/util/Factory.sol

36        function newLiquidityPool(
37            uint64 poolId,
38            bytes16 trancheId,
39            address currency,
40            address trancheToken,
41            address investmentManager,
42            address[] calldata wards
43:       ) public auth returns (address) {

81        function newTrancheToken(
82            uint64 poolId,
83            bytes16 trancheId,
84            string memory name,
85            string memory symbol,
86            uint8 decimals,
87            address[] calldata trancheTokenWards,
88            address[] calldata restrictionManagerWards
89:       ) public auth returns (address) {

```
*GitHub*: [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L36-L43), [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L81-L89)

</details>




### [N&#x2011;02] Event is not properly `indexed`
Index event fields make the field more quickly accessible [to off-chain tools](https://ethereum.stackexchange.com/questions/40396/can-somebody-please-explain-the-concept-of-event-indexing) that parse events. This is especially useful when it comes to filtering based on an address. However, note that each index field costs extra gas during emission, so it's not necessarily best to index the maximum allowed per event (three fields). Where applicable, each `event` should use three `indexed` fields if there are three or more fields, and gas usage is not particularly of concern for the events in question. If there are fewer than three applicable fields, all of the applicable fields should be indexed.

*There are 8 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

84:       event File(bytes32 indexed what, address data);

```
*GitHub*: [84](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L84)

```solidity
File: src/LiquidityPool.sol

78:       event File(bytes32 indexed what, address data);

```
*GitHub*: [78](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L78)

```solidity
File: src/PoolManager.sol

95:       event File(bytes32 indexed what, address data);

```
*GitHub*: [95](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L95)

```solidity
File: src/Root.sol

31:       event RelyContract(address target, address indexed user);

32:       event DenyContract(address target, address indexed user);

```
*GitHub*: [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L31), [32](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L32)

```solidity
File: src/gateway/Gateway.sol

96:       event File(bytes32 indexed what, address data);

```
*GitHub*: [96](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L96)

```solidity
File: src/gateway/routers/axelar/Router.sol

34:       event File(bytes32 indexed what, address addr);

```
*GitHub*: [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L34)

```solidity
File: src/token/Tranche.sol

29:       event File(bytes32 indexed what, address data);

```
*GitHub*: [29](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L29)

</details>




### [N&#x2011;03] Duplicated `require()`/`revert()` checks should be refactored to a modifier or function
The compiler will inline the function, which will avoid `JUMP` instructions usually associated with functions

*There are 12 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

190:          require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

245:          require(liquidityPool != address(0), "InvestmentManager/tranche-does-not-exist");

657           require(
658               LiquidityPoolLike(liquidityPool).checkTransferRestriction(address(0), user, 0),
659               "InvestmentManager/not-a-member"
660:          );

460:          require(depositPrice != 0, "LiquidityPool/deposit-token-price-0");

528:          require(redeemPrice != 0, "LiquidityPool/redeem-token-price-0");

```
*GitHub*: [190](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L190), [245](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L245), [657](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L657-L660), [460](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L460), [528](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L528)

```solidity
File: src/PoolManager.sol

347:          require(currency != 0, "PoolManager/unknown-currency"); // Currency index on the Centrifuge side should start at 1

157:          require(address(trancheToken) != address(0), "PoolManager/unknown-token");

200:          require(pool.createdAt != 0, "PoolManager/invalid-pool");

259:          require(currencyAddress != address(0), "PoolManager/unknown-currency");

```
*GitHub*: [347](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L347), [157](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L157), [200](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L200), [259](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L259)

```solidity
File: src/token/ERC20.sol

107:          require(to != address(0) && to != address(this), "ERC20/invalid-address");

109:          require(balance >= value, "ERC20/insufficient-balance");

179:                  require(allowed >= value, "ERC20/insufficient-allowance");

```
*GitHub*: [107](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L107), [109](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L109), [179](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L179)


### [N&#x2011;04] Common functions should be refactored to a common base contract
The functions below have the same implementation as is seen in other files. The functions should be refactored into functions of a common base contract

*There are 2 instances of this issue:*

```solidity
File: src/util/Auth.sol

/// @audit seen in src/token/ERC20.sol
14        function rely(address user) external auth {
15            wards[user] = 1;
16            emit Rely(user);
17:       }

/// @audit seen in src/token/ERC20.sol
20        function deny(address user) external auth {
21            wards[user] = 0;
22            emit Deny(user);
23:       }

```
*GitHub*: [14](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L14-L17), [20](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L20-L23)


### [N&#x2011;05] Open TODOs
Code architecture, incentives, and error handling/reporting questions/issues should be resolved before deployment

*There are 2 instances of this issue:*

```solidity
File: src/gateway/Messages.sol

149:          // TODO(nuno): Now, we encode `tokenName` as a 128-bytearray by first encoding `tokenName`

739:          // TODO(nuno): Now, we encode `tokenName` as a 128-bytearray by first encoding `tokenName`

```
*GitHub*: [149](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L149), [739](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L739)


### [N&#x2011;06] Events that mark critical parameter changes should contain both the old and the new value
This should especially be done if the new value is not required to be different from the old value

*There are 2 instances of this issue:*

```solidity
File: src/LiquidityPool.sol

/// @audit updatePrice()
327:          emit UpdatePrice(price);

```
*GitHub*: [327](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L327)

```solidity
File: src/gateway/Gateway.sol

/// @audit updateOutgoingRouter()
149:          emit UpdateOutgoingRouter(router);

```
*GitHub*: [149](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L149)


### [N&#x2011;07] Constant redefined elsewhere
Consider defining in only one contract so that values cannot become out of sync when only one location is updated. A [cheap way](https://medium.com/coinmonks/gas-cost-of-solidity-library-functions-dbe0cedd4678) to store constants in a single location is to create an `internal constant` in a `library`. If the variable is a local cache of another contract's value, consider making the cache variable internal or private, which will require external users to query the contract with the source of truth, so that callers don't get out of sync.

*There are 5 instances of this issue:*

```solidity
File: src/PoolManager.sol

/// @audit seen in src/InvestmentManager.sol 
81:       EscrowLike public immutable escrow;

```
*GitHub*: [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L81)

```solidity
File: src/Root.sol

/// @audit seen in src/PoolManager.sol 
19:       address public immutable escrow;

```
*GitHub*: [19](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L19)

```solidity
File: src/admins/PauseAdmin.sol

/// @audit seen in src/admins/DelayedAdmin.sol 
11:       Root public immutable root;

```
*GitHub*: [11](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L11)

```solidity
File: src/gateway/Gateway.sol

/// @audit seen in src/admins/PauseAdmin.sol 
85:       RootLike public immutable root;

```
*GitHub*: [85](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L85)

```solidity
File: src/util/Factory.sol

/// @audit seen in src/gateway/Gateway.sol 
72:       address immutable root;

```
*GitHub*: [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L72)


### [N&#x2011;08] Lines are too long
Usually lines in source code are limited to [80](https://softwareengineering.stackexchange.com/questions/148677/why-is-80-characters-the-standard-limit-for-code-width) characters. Today's screens are much larger so it's reasonable to stretch this in some cases. The solidity style guide recommends a maximumum line length of [120 characters](https://docs.soliditylang.org/en/v0.8.17/style-guide.html#maximum-line-length), so the lines below should be split when they reach that length.

*There are 43 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

111:      /// @notice Request deposit. Liquidity pools have to request investments from Centrifuge before actual tranche tokens can be minted.

112:      ///         The deposit requests are added to the order book on Centrifuge. Once the next epoch is executed on Centrifuge,

143:      /// @notice Request tranche token redemption. Liquidity pools have to request redemptions from Centrifuge before actual currency payouts can be done.

144:      ///         The redemption requests are added to the order book on Centrifuge. Once the next epoch is executed on Centrifuge,

147:      /// @dev    The user tranche tokens required to fullfill the redemption request have to be locked, even though the currency payout can only happen after epoch execution.

251:          LiquidityPoolLike(liquidityPool).mint(address(escrow), trancheTokensPayout); // mint to escrow. Recepeint can claim by calling withdraw / redeem

273:          LiquidityPoolLike(liquidityPool).burn(address(escrow), trancheTokensPayout); // burned redeemed tokens from escrow

323:      /// @dev Calculates the amount of shares / tranche tokens that any user would get for the amount of currency / assets provided.

423:      ///         In case user's invest order was fullfilled (partially or in full) on Centrifuge during epoch execution MaxDeposit and MaxMint are increased and tranche tokens can be transferred to user's wallet on calling processDeposit.

424:      ///         Note: The currency required to fullfill the invest order is already locked in escrow upon calling requestDeposit.

426:      /// @return trancheTokenAmount the amount of tranche tokens transferred to the user's wallet after successful deposit.

444:      ///         In case user's invest order was fullfilled on Centrifuge during epoch execution MaxDeposit and MaxMint are increased

446:      ///         Note: The currency amount required to fullfill the invest order is already locked in escrow upon calling requestDeposit.

447:      ///         Note: The tranche tokens are already minted on collectInvest and are deposited to the escrow account until the users calls mint, or deposit.

472:          _decreaseDepositLimits(user, liquidityPool, currencyAmount, trancheTokenAmount); // decrease the possible deposit limits

483:      ///         In case user's redempion order was fullfilled on Centrifuge during epoch execution MaxRedeem and MaxWithdraw

484:      ///         are increased and LiquidityPool currency can be transferred to user's wallet on calling processRedeem or processWithdraw.

488:      /// @return currencyAmount the amount of liquidityPool assets received for the amount of redeemed/burned tranche tokens.

510:      ///         In case user's redempion order was fullfilled on Centrifuge during epoch execution MaxRedeem and MaxWithdraw

511:      ///         are increased and LiquidityPool currency can be transferred to user's wallet on calling processRedeem or processWithdraw.

512:      ///         Note: The trancheTokenAmount required to fullfill the redemption order was already locked in escrow upon calling requestRedeem and burned upon collectRedeem.

514:      /// @return trancheTokenAmount the amount of trancheTokens redeemed/burned required to receive the currencyAmount payout/withdrawel.

544:          _decreaseRedemptionLimits(user, liquidityPool, currencyAmount, trancheTokenAmount); // decrease the possible deposit limits

598:          uint256 currencyAmountInPriceDecimals = _toPriceDecimals(currencyAmount, currencyDecimals, liquidityPool).mulDiv(

664:      /// @dev    Safe type conversion from uint256 to uint128. Revert if value is too big to be stored with uint128. Avoid data loss.

```
*GitHub*: [111](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L111), [112](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L112), [143](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L143), [144](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L144), [147](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L147), [251](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L251), [273](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L273), [323](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L323), [423](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L423), [424](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L424), [426](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L426), [444](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L444), [446](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L446), [447](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L447), [472](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L472), [483](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L483), [484](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L484), [488](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L488), [510](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L510), [511](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L511), [512](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L512), [514](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L514), [544](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L544), [598](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L598), [664](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L664)

```solidity
File: src/LiquidityPool.sol

48:   /// @dev    Each Liquidity Pool is a tokenized vault issuing shares of Centrifuge tranches as restricted ERC20 tokens against currency deposits based on the current share price.

49:   ///         This is extending the EIP4626 standard by 'requestRedeem' & 'requestDeposit' functions, where redeem and deposit orders are submitted to the pools

50:   ///         to be included in the execution of the following epoch. After execution users can use the deposit, mint, redeem and withdraw functions to

59:       ///         Each tranche of a Centrifuge pool can have multiple Liquidity Pools. A Liquidity Pool for each supported asset.

129:      /// @return Maximum amount of assets that can be deposited into the Tranche by the receiver after the epoch had been executed on Centrifuge.

154:      /// @notice Maximum amount of shares that can be claimed by the receiver after the epoch has been executed on the Centrifuge side.

169:      /// @return shares that a user would need to redeem in order to receive the given amount of assets -> convertToAssets

174:      /// @notice Withdraw assets after successful epoch execution. Receiver will receive an exact amount of assets for a certain amount of shares that has been redeemed from Owner during epoch execution.

```
*GitHub*: [48](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L48), [49](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L49), [50](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L50), [59](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L59), [129](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L129), [154](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L154), [169](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L169), [174](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L174)

```solidity
File: src/PoolManager.sol

65:       // important: the decimals of the leading pool currency. Liquidity Pool shares have to be denomatimated with the same precision.

176:      /// @notice     Centrifuge pools can support multiple currencies for investing. this function adds a new supported currency to the pool details.

235:      /// @notice A global chain agnostic currency index is maintained on Centrifuge. This function maps a currency from the Centrifuge index to its corresponding address on the evm chain.

310:          require(isAllowedAsPoolCurrency(poolId, currency), "PoolManager/currency-not-supported"); // Currency must be supported by pool

328:          EscrowLike(escrow).approve(liquidityPool, address(investmentManager), type(uint256).max); // Approve investment manager on tranche token for coordinating transfers

329:          EscrowLike(escrow).approve(liquidityPool, liquidityPool, type(uint256).max); // Approve liquidityPool on tranche token to be able to burn

347:          require(currency != 0, "PoolManager/unknown-currency"); // Currency index on the Centrifuge side should start at 1

```
*GitHub*: [65](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L65), [176](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L176), [235](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L235), [310](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L310), [328](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L328), [329](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L329), [347](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L347)

```solidity
File: src/UserEscrow.sol

42:               ///      a transfer is only possible in case receiver has received the full allowance from destination address.

```
*GitHub*: [42](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L42)

```solidity
File: src/token/ERC20.sol

165:              balanceOf[to] = balanceOf[to] + value; // note: we don't need an overflow check here b/c balanceOf[to] <= totalSupply and there is an overflow check below

188:              balanceOf[from] = balance - value; // note: we don't need overflow checks b/c require(balance >= value) and balance <= totalSupply

```
*GitHub*: [165](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L165), [188](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L188)


### [N&#x2011;09] Long functions should be refactored into multiple, smaller, functions


*There is one instance of this issue:*

```solidity
File: src/gateway/Gateway.sol

/// @audit 82 lines (80 in the body)
285:      function handle(bytes calldata message) external onlyIncomingRouter pauseable {

```
*GitHub*: [285](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L285)


### [N&#x2011;10] Variable names that consist of all capital letters should be reserved for `constant`/`immutable` variables
If the variable needs to be different based on which class it comes from, a `view`/`pure` _function_ should be used instead (e.g. like [this](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/76eee35971c2541585e05cbf258510dda7b2fbc6/contracts/token/ERC20/extensions/draft-IERC20Permit.sol#L59)).

*There is one instance of this issue:*

```solidity
File: src/Root.sol

17:       uint256 private MAX_DELAY = 4 weeks;

```
*GitHub*: [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L17)


### [N&#x2011;11] Typos


*There are 29 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

/// @audit fullfilled
113:      ///         liquidity pools can proceed with tranche token payouts in case their orders got fullfilled.

/// @audit fullfill
115:      /// @dev    The user currency amount required to fullfill the deposit request have to be locked,

/// @audit fullfilled
145:      ///         liquidity pools can proceed with currency payouts in case their orders got fullfilled.

/// @audit fullfill
147:      /// @dev    The user tranche tokens required to fullfill the redemption request have to be locked, even though the currency payout can only happen after epoch execution.

/// @audit Recepeint
251:          LiquidityPoolLike(liquidityPool).mint(address(escrow), trancheTokensPayout); // mint to escrow. Recepeint can claim by calling withdraw / redeem

/// @audit uin256
349:      /// @return currencyAmount is type of uin256 to support the EIP4626 Liquidity Pool interface

/// @audit uin256
354:      /// @return trancheTokenAmount type of uin256 to support the EIP4626 Liquidity Pool interface

/// @audit uin256
359:      /// @return currencyAmount type of uin256 to support the EIP4626 Liquidity Pool interface

/// @audit uin256
364:      /// @return trancheTokenAmount type of uin256 to support the EIP4626 Liquidity Pool interface

/// @audit uin256
369:      /// @return trancheTokenAmount is type of uin256 to support the EIP4626 Liquidity Pool interface

/// @audit uin256
382:      /// @return currencyAmount is type of uin256 to support the EIP4626 Liquidity Pool interface

/// @audit uin256
395:      /// @return trancheTokenAmount is type of uin256 to support the EIP4626 Liquidity Pool interface

/// @audit uin256
408:      /// @return currencyAmount is type of uin256 to support the EIP4626 Liquidity Pool interface

/// @audit fullfilled
423:      ///         In case user's invest order was fullfilled (partially or in full) on Centrifuge during epoch execution MaxDeposit and MaxMint are increased and tranche tokens can be transferred to user's wallet on calling processDeposit.

/// @audit fullfill
424:      ///         Note: The currency required to fullfill the invest order is already locked in escrow upon calling requestDeposit.

/// @audit fullfilled
444:      ///         In case user's invest order was fullfilled on Centrifuge during epoch execution MaxDeposit and MaxMint are increased

/// @audit fullfill
446:      ///         Note: The currency amount required to fullfill the invest order is already locked in escrow upon calling requestDeposit.

/// @audit redempion
/// @audit fullfilled
483:      ///         In case user's redempion order was fullfilled on Centrifuge during epoch execution MaxRedeem and MaxWithdraw

/// @audit fullfill
485:      ///         Note: The trancheTokenAmount required to fullfill the redemption order was already locked in escrow

/// @audit redempion
/// @audit fullfilled
510:      ///         In case user's redempion order was fullfilled on Centrifuge during epoch execution MaxRedeem and MaxWithdraw

/// @audit fullfill
512:      ///         Note: The trancheTokenAmount required to fullfill the redemption order was already locked in escrow upon calling requestRedeem and burned upon collectRedeem.

/// @audit withdrawel
514:      /// @return trancheTokenAmount the amount of trancheTokens redeemed/burned required to receive the currencyAmount payout/withdrawel.

```
*GitHub*: [113](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L113), [115](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L115), [145](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L145), [147](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L147), [251](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L251), [349](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L349), [354](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L354), [359](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L359), [364](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L364), [369](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L369), [382](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L382), [395](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L395), [408](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L408), [423](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L423), [424](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L424), [444](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L444), [446](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L446), [483](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L483), [483](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L483), [485](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L485), [510](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L510), [510](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L510), [512](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L512), [514](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L514)

```solidity
File: src/LiquidityPool.sol

/// @audit calcultion
116:      ///         The calcultion is based on the token price from the most recent epoch retrieved from Centrifuge.

```
*GitHub*: [116](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L116)

```solidity
File: src/PoolManager.sol

/// @audit denomatimated
65:       // important: the decimals of the leading pool currency. Liquidity Pool shares have to be denomatimated with the same precision.

/// @audit existng
190:      /// @notice     New tranche details from an existng Centrifuge pool are added.

```
*GitHub*: [65](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L65), [190](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L190)

```solidity
File: src/Root.sol

/// @audit persmissions
97:       /// @param user the address which persmissions should be removed

```
*GitHub*: [97](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L97)

```solidity
File: src/UserEscrow.sol

/// @audit compromized
40:               ///      The check is just an additional protection to secure destination funds in case of compromized auth.

```
*GitHub*: [40](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L40)


### [N&#x2011;12] NatSpec `@param` is missing


*There are 78 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

/// @audit Missing: '@param currencyAmount'
/// @audit Missing: '@param user'
115       /// @dev    The user currency amount required to fullfill the deposit request have to be locked,
116       ///         even though the tranche token payout can only happen after epoch execution.
117:      function requestDeposit(uint256 currencyAmount, address user) public auth {

/// @audit Missing: '@param trancheTokenAmount'
/// @audit Missing: '@param user'
146       ///         If an amount of 0 is passed, this triggers cancelling outstanding redemption orders.
147       /// @dev    The user tranche tokens required to fullfill the redemption request have to be locked, even though the currency payout can only happen after epoch execution.
148:      function requestRedeem(uint256 trancheTokenAmount, address user) public auth {

/// @audit Missing: '@param _assets'
/// @audit Missing: '@param liquidityPool'
323       /// @dev Calculates the amount of shares / tranche tokens that any user would get for the amount of currency / assets provided.
324       ///      The calculation is based on the tranche token price from the most recent epoch retrieved from Centrifuge.
325:      function convertToShares(uint256 _assets, address liquidityPool) public view auth returns (uint256 shares) {

/// @audit Missing: '@param _shares'
/// @audit Missing: '@param liquidityPool'
336       /// @dev Calculates the asset value for an amount of shares / tranche tokens provided.
337       ///      The calculation is based on the tranche token price from the most recent epoch retrieved from Centrifuge.
338:      function convertToAssets(uint256 _shares, address liquidityPool) public view auth returns (uint256 assets) {

/// @audit Missing: '@param user'
/// @audit Missing: '@param currencyAmount'
425       /// @dev    trancheTokenAmount return value is type of uint256 to be compliant with EIP4626 LiquidityPool interface
426       /// @return trancheTokenAmount the amount of tranche tokens transferred to the user's wallet after successful deposit.
427:      function processDeposit(address user, uint256 currencyAmount) public auth returns (uint256 trancheTokenAmount) {

/// @audit Missing: '@param user'
/// @audit Missing: '@param trancheTokenAmount'
449       /// @return currencyAmount the amount of liquidityPool assets invested and locked in escrow in order
450       ///         for the amount of tranche tokens received after successful investment into the pool.
451:      function processMint(address user, uint256 trancheTokenAmount) public auth returns (uint256 currencyAmount) {

/// @audit Missing: '@param trancheTokenAmount'
/// @audit Missing: '@param receiver'
/// @audit Missing: '@param user'
487       /// @notice currencyAmount return value is type of uint256 to be compliant with EIP4626 LiquidityPool interface
488       /// @return currencyAmount the amount of liquidityPool assets received for the amount of redeemed/burned tranche tokens.
489       function processRedeem(uint256 trancheTokenAmount, address receiver, address user)
490           public
491           auth
492:          returns (uint256 currencyAmount)

/// @audit Missing: '@param currencyAmount'
/// @audit Missing: '@param receiver'
/// @audit Missing: '@param user'
513       /// @notice trancheTokenAmount return value is type of uint256 to be compliant with EIP4626 LiquidityPool interface
514       /// @return trancheTokenAmount the amount of trancheTokens redeemed/burned required to receive the currencyAmount payout/withdrawel.
515       function processWithdraw(uint256 currencyAmount, address receiver, address user)
516           public
517           auth
518:          returns (uint256 trancheTokenAmount)

/// @audit Missing: '@param _value'
664       /// @dev    Safe type conversion from uint256 to uint128. Revert if value is too big to be stored with uint128. Avoid data loss.
665       /// @return value - safely converted without data loss
666:      function _toUint128(uint256 _value) internal pure returns (uint128 value) {

/// @audit Missing: '@param _value'
/// @audit Missing: '@param decimals'
/// @audit Missing: '@param liquidityPool'
674       /// @dev    When converting currency to tranche token amounts using the price,
675       ///         all values are normalized to PRICE_DECIMALS
676       function _toPriceDecimals(uint128 _value, uint8 decimals, address liquidityPool)
677           internal
678           view
679:          returns (uint256 value)

```
*GitHub*: [115](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L115-L117), [115](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L115-L117), [146](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L146-L148), [146](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L146-L148), [323](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L323-L325), [323](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L323-L325), [336](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L336-L338), [336](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L336-L338), [425](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L425-L427), [425](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L425-L427), [449](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L449-L451), [449](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L449-L451), [487](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L487-L492), [487](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L487-L492), [487](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L487-L492), [513](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L513-L518), [513](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L513-L518), [513](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L513-L518), [664](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L664-L666), [674](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L674-L679), [674](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L674-L679), [674](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L674-L679)

```solidity
File: src/LiquidityPool.sol

/// @audit Missing: '@param assets'
116       ///         The calcultion is based on the token price from the most recent epoch retrieved from Centrifuge.
117       ///         The actual conversion will likely differ as the price changes between order submission and execution.
118:      function convertToShares(uint256 assets) public view returns (uint256 shares) {

/// @audit Missing: '@param shares'
123       ///         The calculation is based on the token price from the most recent epoch retrieved from Centrifuge.
124       ///         The actual conversion will likely differ as the price changes between order submission and execution.
125:      function convertToAssets(uint256 shares) public view returns (uint256 assets) {

/// @audit Missing: '@param assets'
/// @audit Missing: '@param receiver'
139       /// @notice Collect shares for deposited assets after Centrifuge epoch execution.
140       ///         maxDeposit is the max amount of shares that can be collected.
141:      function deposit(uint256 assets, address receiver) public returns (uint256 shares) {

/// @audit Missing: '@param shares'
/// @audit Missing: '@param receiver'
146       /// @notice Collect shares for deposited assets after Centrifuge epoch execution.
147       ///         maxMint is the max amount of shares that can be collected.
148:      function mint(uint256 shares, address receiver) public returns (uint256 assets) {

/// @audit Missing: '@param assets'
/// @audit Missing: '@param receiver'
/// @audit Missing: '@param owner'
174       /// @notice Withdraw assets after successful epoch execution. Receiver will receive an exact amount of assets for a certain amount of shares that has been redeemed from Owner during epoch execution.
175       /// @return shares that have been redeemed for the exact assets amount
176       function withdraw(uint256 assets, address receiver, address owner)
177           public
178           withApproval(owner)
179:          returns (uint256 shares)

/// @audit Missing: '@param shares'
/// @audit Missing: '@param receiver'
/// @audit Missing: '@param owner'
198       ///         the exact amount of redeemed shares from Owner after epoch execution.
199       /// @return assets payout for the exact amount of redeemed shares
200       function redeem(uint256 shares, address receiver, address owner)
201           public
202           withApproval(owner)
203:          returns (uint256 assets)

/// @audit Missing: '@param assets'
/// @audit Missing: '@param owner'
212       /// @notice Request can only be called by the Owner of the assets or an authorized admin.
213       ///         Asset is locked in the escrow on request submission
214:      function requestDeposit(uint256 assets, address owner) public withApproval(owner) {

/// @audit Missing: '@param shares'
/// @audit Missing: '@param owner'
229       /// @notice Request can only be called by the Owner of the shares or an authorized admin.
230       ///         Shares are locked in the escrow on request submission
231:      function requestRedeem(uint256 shares, address owner) public withApproval(owner) {

/// @audit Missing: '@param assets'
/// @audit Missing: '@param owner'
245       /// @notice Request decreasing the outstanding deposit orders. Will return the assets once the order
246       ///         on Centrifuge is successfully decreased.
247:      function decreaseDepositRequest(uint256 assets, address owner) public withApproval(owner) {

/// @audit Missing: '@param shares'
/// @audit Missing: '@param owner'
251       /// @notice Request decreasing the outstanding redemption orders. Will return the shares once the order
252       ///         on Centrifuge is successfully decreased.
253:      function decreaseRedeemRequest(uint256 shares, address owner) public withApproval(owner) {

/// @audit Missing: '@param receiver'
257       // --- Miscellaneous investment functions ---
258       /// @notice Trigger collecting the deposited funds.
259:      function collectDeposit(address receiver) public {

/// @audit Missing: '@param from'
/// @audit Missing: '@param to'
/// @audit Missing: '@param value'
330       // --- Restriction overrides ---
331       /// @notice Check if the shares are allowed to be transferred.
332:      function checkTransferRestriction(address from, address to, uint256 value) public view returns (bool) {

/// @audit Missing: '@param success'
336       // --- Helpers ---
337       /// @dev In case of unsuccessful tx, parse the revert message
338:      function _successCheck(bool success) internal pure {

```
*GitHub*: [116](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L116-L118), [123](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L123-L125), [139](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L139-L141), [139](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L139-L141), [146](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L146-L148), [146](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L146-L148), [174](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L174-L179), [174](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L174-L179), [174](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L174-L179), [198](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L198-L203), [198](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L198-L203), [198](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L198-L203), [212](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L212-L214), [212](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L212-L214), [229](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L229-L231), [229](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L229-L231), [245](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L245-L247), [245](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L245-L247), [251](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L251-L253), [251](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L251-L253), [257](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L257-L259), [330](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L330-L332), [330](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L330-L332), [330](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L330-L332), [336](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L336-L338)

```solidity
File: src/PoolManager.sol

/// @audit Missing: '@param poolId'
166       /// @notice    New pool details from an existing Centrifuge pool are added.
167       /// @dev       The function can only be executed by the gateway contract.
168:      function addPool(uint64 poolId) public onlyGateway {

/// @audit Missing: '@param poolId'
/// @audit Missing: '@param currency'
177       ///             Adding new currencies allow the creation of new liquidity pools for the underlying Centrifuge pool.
178       /// @dev        The function can only be executed by the gateway contract.
179:      function allowPoolCurrency(uint64 poolId, uint128 currency) public onlyGateway {

/// @audit Missing: '@param poolId'
/// @audit Missing: '@param trancheId'
/// @audit Missing: '@param tokenName'
/// @audit Missing: '@param tokenSymbol'
/// @audit Missing: '@param decimals'
190       /// @notice     New tranche details from an existng Centrifuge pool are added.
191       /// @dev        The function can only be executed by the gateway contract.
192       function addTranche(
193           uint64 poolId,
194           bytes16 trancheId,
195           string memory tokenName,
196           string memory tokenSymbol,
197           uint8 decimals
198:      ) public onlyGateway {

/// @audit Missing: '@param currency'
/// @audit Missing: '@param currencyAddress'
236       ///         The chain agnostic currency id has to be used to pass currency information to the Centrifuge.
237       /// @dev    This function can only be executed by the gateway contract.
238:      function addCurrency(uint128 currency, address currencyAddress) public onlyGateway {

```
*GitHub*: [166](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L166-L168), [177](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L177-L179), [177](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L177-L179), [190](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L190-L198), [190](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L190-L198), [190](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L190-L198), [190](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L190-L198), [190](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L190-L198), [236](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L236-L238), [236](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L236-L238)

```solidity
File: src/Root.sol

/// @audit Missing: '@param user'
88        /// @param target the address of the contract
89        /// @param user the address which should get ward permissions
90:       function relyContract(address target, address user) public auth {

/// @audit Missing: '@param user'
96        /// @param target the address of the contract
97        /// @param user the address which persmissions should be removed
98:       function denyContract(address target, address user) public auth {

```
*GitHub*: [88](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L88-L90), [96](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L96-L98)

```solidity
File: src/admins/DelayedAdmin.sol

/// @audit Missing: '@param root_'
15        // --- Events ---
16        event File(bytes32 indexed what, address indexed data);
17    
18:       constructor(address root_) {

```
*GitHub*: [15](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L15-L18)

```solidity
File: src/admins/PauseAdmin.sol

/// @audit Missing: '@param root_'
18        // --- Events ---
19        event File(bytes32 indexed what, address indexed data);
20    
21:       constructor(address root_) {

```
*GitHub*: [18](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L18-L21)

```solidity
File: src/gateway/Messages.sol

/// @audit Missing: '@param _msg'
292       // An optimised `parseTransfer` function that saves gas by ignoring the `sender` field and that
293       // parses and returns the `recipient` as an `address` instead of the `bytes32` the message holds.
294       function parseIncomingTransfer(bytes memory _msg)
295           internal
296           pure
297:          returns (uint128 currency, address recipient, uint128 amount)

/// @audit Missing: '@param poolId'
/// @audit Missing: '@param trancheId'
/// @audit Missing: '@param sender'
/// @audit Missing: '@param destinationDomain'
/// @audit Missing: '@param destinationAddress'
/// @audit Missing: '@param amount'
330       // for the `destinationAddress` field by using the default `formatTransferTrancheTokens` implementation
331       // by appending 12 zeros to the evm-based `destinationAddress`.
332       function formatTransferTrancheTokens(
333           uint64 poolId,
334           bytes16 trancheId,
335           bytes32 sender,
336           bytes9 destinationDomain,
337           address destinationAddress,
338           uint128 amount
339:      ) internal pure returns (bytes memory) {

/// @audit Missing: '@param _msg'
349       // Parse a TransferTrancheTokens to an EVM-based `destinationAddress` (20-byte long).
350       // We ignore the `sender` and the `domain` since it's not relevant when parsing an incoming message.
351       function parseTransferTrancheTokens20(bytes memory _msg)
352           internal
353           pure
354:          returns (uint64 poolId, bytes16 trancheId, address destinationAddress, uint128 amount)

/// @audit Missing: '@param domain'
834       // Utils
835   
836:      function formatDomain(Domain domain) public pure returns (bytes9) {

```
*GitHub*: [292](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L292-L297), [330](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L330-L339), [330](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L330-L339), [330](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L330-L339), [330](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L330-L339), [330](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L330-L339), [330](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L330-L339), [349](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L349-L354), [834](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L834-L836)

```solidity
File: src/gateway/routers/axelar/Router.sol

/// @audit Missing: '@param axelarGateway_'
33        // --- Events ---
34        event File(bytes32 indexed what, address addr);
35    
36:       constructor(address axelarGateway_) {

```
*GitHub*: [33](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L33-L36)

```solidity
File: src/util/SafeTransferLib.sol

/// @audit Missing: '@param token'
/// @audit Missing: '@param from'
/// @audit Missing: '@param value'
13        /// @param to The destination address of the transfer
14        /// @param value The amount to be transferred
15:       function safeTransferFrom(address token, address from, address to, uint256 value) internal {

/// @audit Missing: '@param token'
/// @audit Missing: '@param value'
24        /// @param to The recipient of the transfer
25        /// @param value The value of the transfer
26:       function safeTransfer(address token, address to, uint256 value) internal {

/// @audit Missing: '@param token'
/// @audit Missing: '@param value'
34        /// @param to The target of the approval
35        /// @param value The amount of the given token the target will be allowed to spend
36:       function safeApprove(address token, address to, uint256 value) internal {

```
*GitHub*: [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L13-L15), [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L13-L15), [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L13-L15), [24](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L24-L26), [24](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L24-L26), [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L34-L36), [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L34-L36)

</details>




### [N&#x2011;13] NatSpec `@return` argument is missing


*There are 21 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

/// @audit Missing: '@return'
323       /// @dev Calculates the amount of shares / tranche tokens that any user would get for the amount of currency / assets provided.
324       ///      The calculation is based on the tranche token price from the most recent epoch retrieved from Centrifuge.
325:      function convertToShares(uint256 _assets, address liquidityPool) public view auth returns (uint256 shares) {

/// @audit Missing: '@return'
336       /// @dev Calculates the asset value for an amount of shares / tranche tokens provided.
337       ///      The calculation is based on the tranche token price from the most recent epoch retrieved from Centrifuge.
338:      function convertToAssets(uint256 _shares, address liquidityPool) public view auth returns (uint256 assets) {

/// @audit Missing: '@return'
425       /// @dev    trancheTokenAmount return value is type of uint256 to be compliant with EIP4626 LiquidityPool interface
426       /// @return trancheTokenAmount the amount of tranche tokens transferred to the user's wallet after successful deposit.
427:      function processDeposit(address user, uint256 currencyAmount) public auth returns (uint256 trancheTokenAmount) {

/// @audit Missing: '@return'
487       /// @notice currencyAmount return value is type of uint256 to be compliant with EIP4626 LiquidityPool interface
488       /// @return currencyAmount the amount of liquidityPool assets received for the amount of redeemed/burned tranche tokens.
489       function processRedeem(uint256 trancheTokenAmount, address receiver, address user)
490           public
491           auth
492:          returns (uint256 currencyAmount)

/// @audit Missing: '@return'
513       /// @notice trancheTokenAmount return value is type of uint256 to be compliant with EIP4626 LiquidityPool interface
514       /// @return trancheTokenAmount the amount of trancheTokens redeemed/burned required to receive the currencyAmount payout/withdrawel.
515       function processWithdraw(uint256 currencyAmount, address receiver, address user)
516           public
517           auth
518:          returns (uint256 trancheTokenAmount)

/// @audit Missing: '@return'
664       /// @dev    Safe type conversion from uint256 to uint128. Revert if value is too big to be stored with uint128. Avoid data loss.
665       /// @return value - safely converted without data loss
666:      function _toUint128(uint256 _value) internal pure returns (uint128 value) {

/// @audit Missing: '@return'
674       /// @dev    When converting currency to tranche token amounts using the price,
675       ///         all values are normalized to PRICE_DECIMALS
676       function _toPriceDecimals(uint128 _value, uint8 decimals, address liquidityPool)
677           internal
678           view
679:          returns (uint256 value)

```
*GitHub*: [323](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L323-L325), [336](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L336-L338), [425](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L425-L427), [487](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L487-L492), [513](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L513-L518), [664](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L664-L666), [674](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L674-L679)

```solidity
File: src/LiquidityPool.sol

/// @audit Missing: '@return'
109       // --- ERC4626 functions ---
110       /// @return Total value of the shares, denominated in the asset of this Liquidity Pools
111:      function totalAssets() public view returns (uint256) {

/// @audit Missing: '@return'
116       ///         The calcultion is based on the token price from the most recent epoch retrieved from Centrifuge.
117       ///         The actual conversion will likely differ as the price changes between order submission and execution.
118:      function convertToShares(uint256 assets) public view returns (uint256 shares) {

/// @audit Missing: '@return'
123       ///         The calculation is based on the token price from the most recent epoch retrieved from Centrifuge.
124       ///         The actual conversion will likely differ as the price changes between order submission and execution.
125:      function convertToAssets(uint256 shares) public view returns (uint256 assets) {

/// @audit Missing: '@return'
139       /// @notice Collect shares for deposited assets after Centrifuge epoch execution.
140       ///         maxDeposit is the max amount of shares that can be collected.
141:      function deposit(uint256 assets, address receiver) public returns (uint256 shares) {

/// @audit Missing: '@return'
146       /// @notice Collect shares for deposited assets after Centrifuge epoch execution.
147       ///         maxMint is the max amount of shares that can be collected.
148:      function mint(uint256 shares, address receiver) public returns (uint256 assets) {

/// @audit Missing: '@return'
174       /// @notice Withdraw assets after successful epoch execution. Receiver will receive an exact amount of assets for a certain amount of shares that has been redeemed from Owner during epoch execution.
175       /// @return shares that have been redeemed for the exact assets amount
176       function withdraw(uint256 assets, address receiver, address owner)
177           public
178           withApproval(owner)
179:          returns (uint256 shares)

/// @audit Missing: '@return'
198       ///         the exact amount of redeemed shares from Owner after epoch execution.
199       /// @return assets payout for the exact amount of redeemed shares
200       function redeem(uint256 shares, address receiver, address owner)
201           public
202           withApproval(owner)
203:          returns (uint256 assets)

/// @audit Missing: '@return'
330       // --- Restriction overrides ---
331       /// @notice Check if the shares are allowed to be transferred.
332:      function checkTransferRestriction(address from, address to, uint256 value) public view returns (bool) {

```
*GitHub*: [109](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L109-L111), [116](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L116-L118), [123](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L123-L125), [139](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L139-L141), [146](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L146-L148), [174](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L174-L179), [198](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L198-L203), [330](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L330-L332)

```solidity
File: src/gateway/Messages.sol

/// @audit Missing: '@return'
292       // An optimised `parseTransfer` function that saves gas by ignoring the `sender` field and that
293       // parses and returns the `recipient` as an `address` instead of the `bytes32` the message holds.
294       function parseIncomingTransfer(bytes memory _msg)
295           internal
296           pure
297:          returns (uint128 currency, address recipient, uint128 amount)

/// @audit Missing: '@return'
330       // for the `destinationAddress` field by using the default `formatTransferTrancheTokens` implementation
331       // by appending 12 zeros to the evm-based `destinationAddress`.
332       function formatTransferTrancheTokens(
333           uint64 poolId,
334           bytes16 trancheId,
335           bytes32 sender,
336           bytes9 destinationDomain,
337           address destinationAddress,
338           uint128 amount
339:      ) internal pure returns (bytes memory) {

/// @audit Missing: '@return'
349       // Parse a TransferTrancheTokens to an EVM-based `destinationAddress` (20-byte long).
350       // We ignore the `sender` and the `domain` since it's not relevant when parsing an incoming message.
351       function parseTransferTrancheTokens20(bytes memory _msg)
352           internal
353           pure
354:          returns (uint64 poolId, bytes16 trancheId, address destinationAddress, uint128 amount)

/// @audit Missing: '@return'
834       // Utils
835   
836:      function formatDomain(Domain domain) public pure returns (bytes9) {

```
*GitHub*: [292](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L292-L297), [330](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L330-L339), [349](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L349-L354), [834](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L834-L836)

```solidity
File: src/token/Tranche.sol

/// @audit Missing: '@return'
101       ///         a call is not performed by the trusted forwarder or the calldata length is less than
102       ///         20 bytes (an address length).
103:      function _msgSender() internal view virtual override returns (address sender) {

```
*GitHub*: [101](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L101-L103)

```solidity
File: src/util/Context.sol

/// @audit Missing: '@return'
10    ///         is concerned).
11    /// @dev    Adapted from OpenZeppelin Contracts v4.4.1 (utils/Context.sol)
12    abstract contract Context {
13:       function _msgSender() internal view virtual returns (address) {

```
*GitHub*: [10](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Context.sol#L10-L13)


### [N&#x2011;14] Assembly blocks should have extensive comments
Assembly blocks take a lot more time to audit than normal Solidity code, and often have gotchas and side-effects that the Solidity versions of the same code do not. Consider adding more comments explaining what is being done in every step of the assembly code, and describe why assembly is being used instead of Solidity.

*There are 4 instances of this issue:*

```solidity
File: src/LiquidityPool.sol

340               assembly {
341                   let ptr := mload(0x40)
342                   let size := returndatasize()
343                   returndatacopy(ptr, 0, size)
344                   revert(ptr, size)
345:              }

```
*GitHub*: [340](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L340-L345)

```solidity
File: src/gateway/Messages.sol

882           assembly {
883               result := mload(add(source, 32))
884:          }

```
*GitHub*: [882](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L882-L884)

```solidity
File: src/token/ERC20.sol

201               assembly {
202                   r := mload(add(signature, 0x20))
203                   s := mload(add(signature, 0x40))
204                   v := byte(0, mload(add(signature, 0x60)))
205:              }

```
*GitHub*: [201](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L201-L205)

```solidity
File: src/token/Tranche.sol

107               assembly {
108                   sender := shr(96, calldataload(sub(calldatasize(), 20)))
109:              }

```
*GitHub*: [107](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L107-L109)


### [N&#x2011;15] Visibility should be set explicitly rather than defaulting to `internal`


*There are 3 instances of this issue:*

```solidity
File: src/UserEscrow.sol

17:       mapping(address => mapping(address => uint256)) destinations;

```
*GitHub*: [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L17)

```solidity
File: src/util/Factory.sol

27:       address immutable root;

72:       address immutable root;

```
*GitHub*: [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L27), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L72)


### [N&#x2011;16] Function ordering does not follow the Solidity style guide
According to the [Solidity style guide](https://docs.soliditylang.org/en/v0.8.17/style-guide.html#order-of-functions), functions should be laid out in the following order :`constructor()`, `receive()`, `fallback()`, `external`, `public`, `internal`, `private`, but the cases below do not follow this pattern

*There are 10 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

/// @audit _deposit() came earlier
489       function processRedeem(uint256 trancheTokenAmount, address receiver, address user)
490           public
491           auth
492:          returns (uint256 currencyAmount)

/// @audit _redeem() came earlier
551:      function calculateDepositPrice(address user, address liquidityPool) public view returns (uint256 depositPrice) {

```
*GitHub*: [489](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L489-L492), [551](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L551)

```solidity
File: src/LiquidityPool.sol

/// @audit mint() came earlier
155:      function maxMint(address receiver) external view returns (uint256 maxShares) {

```
*GitHub*: [155](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L155)

```solidity
File: src/gateway/Gateway.sol

/// @audit cancelRedeemOrder() came earlier
285:      function handle(bytes calldata message) external onlyIncomingRouter pauseable {

```
*GitHub*: [285](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L285)

```solidity
File: src/gateway/Messages.sol

/// @audit parseUpdateTrancheInvestmentLimit() came earlier
836:      function formatDomain(Domain domain) public pure returns (bytes9) {

```
*GitHub*: [836](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L836)

```solidity
File: src/token/ERC20.sol

/// @audit _calculateDomainSeparator() came earlier
79:       function DOMAIN_SEPARATOR() external view returns (bytes32) {

/// @audit transferFrom() came earlier
131:      function approve(address spender, uint256 value) external returns (bool) {

/// @audit mint() came earlier
172:      function burn(address from, uint256 value) external auth {

/// @audit _isValidSignature() came earlier
216:      function permit(address owner, address spender, uint256 value, uint256 deadline, bytes memory signature) public {

/// @audit permit() came earlier
239:      function permit(address owner, address spender, uint256 value, uint256 deadline, uint8 v, bytes32 r, bytes32 s)

```
*GitHub*: [79](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L79), [131](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L131), [172](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L172), [216](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L216), [239](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L239)


### [N&#x2011;17] Contract does not follow the Solidity style guide's suggested layout ordering
The [style guide](https://docs.soliditylang.org/en/v0.8.16/style-guide.html#order-of-layout) says that, within a contract, the ordering should be 1) Type declarations, 2) State variables, 3) Events, 4) Modifiers, and 5) Functions, but the contract(s) below do not follow this ordering

*There are 9 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

/// @audit function constructor came earlier
97        modifier onlyGateway() {
98            require(msg.sender == address(gateway), "InvestmentManager/not-the-gateway");
99            _;
100:      }

```
*GitHub*: [97](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L97-L100)

```solidity
File: src/LiquidityPool.sol

/// @audit function constructor came earlier
97        modifier withApproval(address owner) {
98            require(msg.sender == owner, "LiquidityPool/no-approval");
99            _;
100:      }

```
*GitHub*: [97](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L97-L100)

```solidity
File: src/PoolManager.sol

/// @audit function constructor came earlier
114       modifier onlyGateway() {
115           require(msg.sender == address(gateway), "PoolManager/not-the-gateway");
116           _;
117:      }

```
*GitHub*: [114](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L114-L117)

```solidity
File: src/admins/PauseAdmin.sol

/// @audit function constructor came earlier
28        modifier canPause() {
29            require(pausers[msg.sender] == 1, "PauseAdmin/not-authorized-to-pause");
30            _;
31:       }

```
*GitHub*: [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L28-L31)

```solidity
File: src/gateway/Gateway.sol

/// @audit function constructor came earlier
109       modifier onlyInvestmentManager() {
110           require(msg.sender == address(investmentManager), "Gateway/only-investment-manager-allowed-to-call");
111           _;
112:      }

```
*GitHub*: [109](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L109-L112)

```solidity
File: src/gateway/routers/axelar/Router.sol

/// @audit function constructor came earlier
43        modifier onlyCentrifugeChainOrigin(string calldata sourceChain, string calldata sourceAddress) {
44            require(msg.sender == address(axelarGateway), "AxelarRouter/invalid-origin");
45            require(
46                keccak256(bytes(axelarCentrifugeChainId)) == keccak256(bytes(sourceChain)),
47                "AxelarRouter/invalid-source-chain"
48            );
49            require(
50                keccak256(bytes(axelarCentrifugeChainAddress)) == keccak256(bytes(sourceAddress)),
51                "AxelarRouter/invalid-source-address"
52            );
53            _;
54:       }

```
*GitHub*: [43](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L43-L54)

```solidity
File: src/token/ERC20.sol

/// @audit function constructor came earlier
51        modifier auth() {
52            // Custom auth modifier that uses _msgSender()
53            require(wards[_msgSender()] == 1, "Auth/not-authorized");
54            _;
55:       }

```
*GitHub*: [51](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L51-L55)

```solidity
File: src/token/Tranche.sol

/// @audit function constructor came earlier
35        modifier restricted(address from, address to, uint256 value) {
36            uint8 restrictionCode = detectTransferRestriction(from, to, value);
37            require(restrictionCode == restrictionManager.SUCCESS_CODE(), messageForTransferRestriction(restrictionCode));
38            _;
39:       }

```
*GitHub*: [35](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L35-L39)

```solidity
File: src/util/Auth.sol

/// @audit function deny came earlier
26        modifier auth() {
27            require(wards[msg.sender] == 1, "Auth/not-authorized");
28            _;
29:       }

```
*GitHub*: [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L26-L29)

</details>




### [N&#x2011;18] Interfaces should be indicated with an `I` prefix in the contract name


*There are 28 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/Escrow.sol

7:    interface ApproveLike {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L7)

```solidity
File: src/InvestmentManager.sol

8:    interface GatewayLike {

23:   interface ERC20Like {

31:   interface LiquidityPoolLike is ERC20Like {

41:   interface PoolManagerLike {

49:   interface EscrowLike {

53:   interface UserEscrowLike {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L8), [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L23), [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L31), [41](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L41), [49](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L49), [53](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L53)

```solidity
File: src/LiquidityPool.sol

9:    interface ERC20PermitLike {

16:   interface TrancheTokenLike is IERC20, ERC20PermitLike {

```
*GitHub*: [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L9), [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L16)

```solidity
File: src/PoolManager.sol

11:   interface GatewayLike {

30:   interface LiquidityPoolLike {

40:   interface EscrowLike {

44:   interface ERC2771Like {

48:   interface AuthLike {

```
*GitHub*: [11](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L11), [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L30), [40](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L40), [44](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L44), [48](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L48)

```solidity
File: src/Root.sol

6:    interface AuthLike {

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L6)

```solidity
File: src/UserEscrow.sol

7:    interface ERC20Like {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L7)

```solidity
File: src/gateway/Gateway.sol

41:   interface PoolManagerLike {

64:   interface RouterLike {

68:   interface AuthLike {

72:   interface RootLike {

```
*GitHub*: [41](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L41), [64](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L64), [68](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L68), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L72)

```solidity
File: src/gateway/routers/axelar/Router.sol

6:    interface AxelarGatewayLike {

18:   interface GatewayLike {

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L6), [18](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L18)

```solidity
File: src/token/RestrictionManager.sol

6:    interface MemberlistLike {

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L6)

```solidity
File: src/token/Tranche.sol

7:    interface TrancheTokenLike is IERC20 {

12:   interface ERC1404Like {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L7), [12](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L12)

```solidity
File: src/util/Factory.sol

9:    interface RootLike {

13:   interface LiquidityPoolFactoryLike {

55:   interface TrancheTokenFactoryLike {

```
*GitHub*: [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L9), [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L13), [55](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L55)

</details>




### [N&#x2011;19] Add inline comments for unnamed variables
`function foo(address x, address)` -> `function foo(address x, address /* y */)`

*There are 377 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/Escrow.sol

8:        function approve(address, uint256) external returns (bool);

24:           SafeTransferLib.safeApprove(token, spender, value);

25:           emit Approve(token, spender, value);

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L8), [24](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L24), [25](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L25)

```solidity
File: src/InvestmentManager.sol

27:       function mint(address, uint256) external;

28:       function burn(address, uint256) external;

107:          emit File(what, data);

124:          poolManager.isAllowedAsPoolCurrency(lPool.poolId(), currency);

126:          _isAllowedToInvest(lPool.poolId(), lPool.trancheId(), currency, user);

130:                  lPool.poolId(), lPool.trancheId(), user, poolManager.currencyAddressToId(lPool.asset())

136:          SafeTransferLib.safeTransferFrom(currency, user, address(escrow), _currencyAmount);

139:              lPool.poolId(), lPool.trancheId(), user, poolManager.currencyAddressToId(lPool.asset()), _currencyAmount

157:          _isAllowedToInvest(lPool.poolId(), lPool.trancheId(), lPool.asset(), user);

162:                  lPool.poolId(), lPool.trancheId(), user, poolManager.currencyAddressToId(lPool.asset())

170:              lPool.poolId(), lPool.trancheId(), user, poolManager.currencyAddressToId(lPool.asset()), _trancheTokenAmount

177:          require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

190:          require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

202:          require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

213:          require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

228:          address liquidityPool = poolManager.getLiquidityPool(poolId, trancheId, currency);

244:          address liquidityPool = poolManager.getLiquidityPool(poolId, trancheId, _currency);

251:          LiquidityPoolLike(liquidityPool).mint(address(escrow), trancheTokensPayout); // mint to escrow. Recepeint can claim by calling withdraw / redeem

252:          _updateLiquidityPoolPrice(liquidityPool, currencyPayout, trancheTokensPayout);

265:          address liquidityPool = poolManager.getLiquidityPool(poolId, trancheId, _currency);

272:          userEscrow.transferIn(_currency, address(escrow), recipient, currencyPayout);

273:          LiquidityPoolLike(liquidityPool).burn(address(escrow), trancheTokensPayout); // burned redeemed tokens from escrow

274:          _updateLiquidityPoolPrice(liquidityPool, currencyPayout, trancheTokensPayout);

287:          address liquidityPool = poolManager.getLiquidityPool(poolId, trancheId, _currency);

291:          SafeTransferLib.safeTransferFrom(_currency, address(escrow), user, currencyPayout);

304:          address liquidityPool = poolManager.getLiquidityPool(poolId, trancheId, _currency);

308:              LiquidityPoolLike(liquidityPool).checkTransferRestriction(address(0), user, 0),

313:              LiquidityPoolLike(liquidityPool).transferFrom(address(escrow), user, trancheTokenPayout),

320:          _totalAssets = convertToAssets(totalSupply, liquidityPool);

376:          uint256 depositPrice = calculateDepositPrice(user, liquidityPool);

379:          trancheTokenAmount = uint256(_calculateTrancheTokenAmount(currencyAmount, liquidityPool, depositPrice));

389:          uint256 depositPrice = calculateDepositPrice(user, liquidityPool);

392:          currencyAmount = uint256(_calculateCurrencyAmount(trancheTokenAmount, liquidityPool, depositPrice));

402:          uint256 redeemPrice = calculateRedeemPrice(user, liquidityPool);

405:          trancheTokenAmount = uint256(_calculateTrancheTokenAmount(currencyAmount, liquidityPool, redeemPrice));

415:          uint256 redeemPrice = calculateRedeemPrice(user, liquidityPool);

418:          currencyAmount = uint256(_calculateCurrencyAmount(trancheTokenAmount, liquidityPool, redeemPrice));

435:          uint256 depositPrice = calculateDepositPrice(user, liquidityPool);

438:          uint128 _trancheTokenAmount = _calculateTrancheTokenAmount(_currencyAmount, liquidityPool, depositPrice);

439:          _deposit(_trancheTokenAmount, _currencyAmount, liquidityPool, user);

459:          uint256 depositPrice = calculateDepositPrice(user, liquidityPool);

462:          uint128 _currencyAmount = _calculateCurrencyAmount(_trancheTokenAmount, liquidityPool, depositPrice);

463:          _deposit(_trancheTokenAmount, _currencyAmount, liquidityPool, user);

472:          _decreaseDepositLimits(user, liquidityPool, currencyAmount, trancheTokenAmount); // decrease the possible deposit limits

473:          require(lPool.checkTransferRestriction(msg.sender, user, 0), "InvestmentManager/trancheTokens-not-a-member");

475:              lPool.transferFrom(address(escrow), user, trancheTokenAmount),

479:          emit DepositProcessed(liquidityPool, user, currencyAmount);

501:          uint256 redeemPrice = calculateRedeemPrice(user, liquidityPool);

504:          uint128 _currencyAmount = _calculateCurrencyAmount(_trancheTokenAmount, liquidityPool, redeemPrice);

505:          _redeem(_trancheTokenAmount, _currencyAmount, liquidityPool, receiver, user);

527:          uint256 redeemPrice = calculateRedeemPrice(user, liquidityPool);

530:          uint128 _trancheTokenAmount = _calculateTrancheTokenAmount(_currencyAmount, liquidityPool, redeemPrice);

531:          _redeem(_trancheTokenAmount, _currencyAmount, liquidityPool, receiver, user);

544:          _decreaseRedemptionLimits(user, liquidityPool, currencyAmount, trancheTokenAmount); // decrease the possible deposit limits

545:          userEscrow.transferOut(lPool.asset(), user, receiver, currencyAmount);

547:          emit RedemptionProcessed(liquidityPool, user, trancheTokenAmount);

557:          depositPrice = _calculatePrice(lpValues.maxDeposit, lpValues.maxMint, liquidityPool);

566:          redeemPrice = _calculatePrice(lpValues.maxWithdraw, lpValues.maxRedeem, liquidityPool);

575:          uint256 currencyAmountInPriceDecimals = _toPriceDecimals(currencyAmount, currencyDecimals, liquidityPool);

577:              _toPriceDecimals(trancheTokenAmount, trancheTokenDecimals, liquidityPool);

580:              10 ** PRICE_DECIMALS, trancheTokenAmountInPriceDecimals, MathLib.Rounding.Down

587:          uint128 price = _toUint128(_calculatePrice(currencyPayout, trancheTokensPayout, liquidityPool));

598:          uint256 currencyAmountInPriceDecimals = _toPriceDecimals(currencyAmount, currencyDecimals, liquidityPool).mulDiv(

599:              10 ** PRICE_DECIMALS, price, MathLib.Rounding.Down

602:          trancheTokenAmount = _fromPriceDecimals(currencyAmountInPriceDecimals, trancheTokenDecimals, liquidityPool);

613:              trancheTokenAmount, trancheTokenDecimals, liquidityPool

616:          currencyAmount = _fromPriceDecimals(currencyAmountInPriceDecimals, currencyDecimals, liquidityPool);

655:          address liquidityPool = poolManager.getLiquidityPool(poolId, trancheId, currency);

658:              LiquidityPoolLike(liquidityPool).checkTransferRestriction(address(0), user, 0),

```
*GitHub*: [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L27), [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L28), [107](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L107), [124](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L124), [126](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L126), [130](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L130), [136](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L136), [139](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L139), [157](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L157), [162](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L162), [170](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L170), [177](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L177), [190](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L190), [202](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L202), [213](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L213), [228](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L228), [244](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L244), [251](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L251), [252](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L252), [265](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L265), [272](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L272), [273](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L273), [274](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L274), [287](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L287), [291](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L291), [304](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L304), [308](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L308), [313](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L313), [320](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L320), [376](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L376), [379](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L379), [389](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L389), [392](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L392), [402](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L402), [405](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L405), [415](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L415), [418](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L418), [435](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L435), [438](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L438), [439](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L439), [459](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L459), [462](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L462), [463](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L463), [472](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L472), [472](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L472), [473](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L473), [475](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L475), [479](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L479), [501](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L501), [504](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L504), [505](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L505), [505](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L505), [527](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L527), [530](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L530), [531](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L531), [531](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L531), [544](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L544), [544](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L544), [545](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L545), [545](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L545), [547](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L547), [557](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L557), [566](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L566), [575](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L575), [577](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L577), [580](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L580), [587](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L587), [598](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L598), [599](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L599), [602](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L602), [613](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L613), [616](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L616), [655](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L655), [658](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L658)

```solidity
File: src/LiquidityPool.sol

50:   ///         to be included in the execution of the following epoch. After execution users can use the deposit, mint, redeem and withdraw functions to

106:          emit File(what, data);

136:          shares = investmentManager.previewDeposit(msg.sender, address(this), assets);

142:          shares = investmentManager.processDeposit(receiver, assets);

143:          emit Deposit(address(this), receiver, assets, shares);

150:          assets = investmentManager.processMint(receiver, shares);

151:          emit Deposit(address(this), receiver, assets, shares);

161:          assets = investmentManager.previewMint(msg.sender, address(this), shares);

171:          shares = investmentManager.previewWithdraw(msg.sender, address(this), assets);

181:          uint256 sharesRedeemed = investmentManager.processWithdraw(assets, receiver, owner);

182:          emit Withdraw(address(this), receiver, owner, assets, sharesRedeemed);

193:          assets = investmentManager.previewRedeem(msg.sender, address(this), shares);

205:          uint256 currencyPayout = investmentManager.processRedeem(shares, receiver, owner);

206:          emit Withdraw(address(this), receiver, owner, currencyPayout, shares);

215:          investmentManager.requestDeposit(assets, owner);

216:          emit DepositRequested(owner, assets);

223:          ERC20PermitLike(asset).permit(owner, address(investmentManager), assets, deadline, v, r, s);

224:          investmentManager.requestDeposit(assets, owner);

225:          emit DepositRequested(owner, assets);

232:          investmentManager.requestRedeem(shares, owner);

233:          emit RedeemRequested(owner, shares);

240:          share.permit(owner, address(investmentManager), shares, deadline, v, r, s);

241:          investmentManager.requestRedeem(shares, owner);

242:          emit RedeemRequested(owner, shares);

248:          investmentManager.decreaseDepositRequest(assets, owner);

254:          investmentManager.decreaseRedeemRequest(shares, owner);

292:          return share.allowance(owner, spender);

295:      function transferFrom(address, address, uint256) public returns (bool) {

301:      function transfer(address, uint256) public returns (bool) {

307:      function approve(address, uint256) public returns (bool) {

313:      function mint(address, uint256) public auth {

318:      function burn(address, uint256) public auth {

333:          return share.checkTransferRestriction(from, to, value);

343:                  returndatacopy(ptr, 0, size)

344:                  revert(ptr, size)

```
*GitHub*: [50](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L50), [106](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L106), [136](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L136), [142](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L142), [143](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L143), [143](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L143), [150](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L150), [151](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L151), [151](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L151), [161](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L161), [171](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L171), [181](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L181), [182](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L182), [182](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L182), [193](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L193), [205](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L205), [206](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L206), [206](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L206), [215](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L215), [216](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L216), [223](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L223), [223](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L223), [223](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L223), [224](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L224), [225](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L225), [232](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L232), [233](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L233), [240](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L240), [240](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L240), [240](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L240), [241](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L241), [242](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L242), [248](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L248), [254](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L254), [292](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L292), [295](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L295), [301](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L301), [307](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L307), [313](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L313), [318](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L318), [333](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L333), [343](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L343), [344](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L344)

```solidity
File: src/PoolManager.sol

124:          emit File(what, data);

132:          SafeTransferLib.safeTransferFrom(currencyAddress, msg.sender, address(escrow), amount);

133:          gateway.transfer(currency, msg.sender, recipient, amount);

142:          TrancheTokenLike trancheToken = TrancheTokenLike(getTrancheToken(poolId, trancheId));

145:          trancheToken.burn(msg.sender, amount);

146:          gateway.transferTrancheTokensToCentrifuge(poolId, trancheId, msg.sender, destinationAddress, amount);

156:          TrancheTokenLike trancheToken = TrancheTokenLike(getTrancheToken(poolId, trancheId));

159:          trancheToken.burn(msg.sender, amount);

161:              poolId, trancheId, msg.sender, destinationChainId, destinationAddress, amount

187:          emit PoolCurrencyAllowed(currency, poolId);

211:          emit TrancheAdded(poolId, trancheId);

220:          TrancheTokenLike trancheToken = TrancheTokenLike(getTrancheToken(poolId, trancheId));

223:          trancheToken.file("name", tokenName);

224:          trancheToken.file("symbol", tokenSymbol);

228:          TrancheTokenLike trancheToken = TrancheTokenLike(getTrancheToken(poolId, trancheId));

232:          memberlist.updateMember(user, validUntil);

254:          emit CurrencyAdded(currency, currencyAddress);

261:          EscrowLike(escrow).approve(currencyAddress, address(this), amount);

262:          SafeTransferLib.safeTransferFrom(currencyAddress, address(escrow), recipient, amount);

269:          TrancheTokenLike trancheToken = TrancheTokenLike(getTrancheToken(poolId, trancheId));

276:          trancheToken.mint(destinationAddress, amount);

303:          emit TrancheTokenDeployed(poolId, trancheId);

310:          require(isAllowedAsPoolCurrency(poolId, currency), "PoolManager/currency-not-supported"); // Currency must be supported by pool

319:              poolId, trancheId, currency, tranche.token, address(investmentManager), liquidityPoolWards

329:          EscrowLike(escrow).approve(liquidityPool, liquidityPool, type(uint256).max); // Approve liquidityPool on tranche token to be able to burn

331:          emit LiquidityPoolDeployed(poolId, trancheId, liquidityPool);

```
*GitHub*: [124](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L124), [132](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L132), [133](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L133), [142](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L142), [145](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L145), [146](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L146), [146](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L146), [156](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L156), [159](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L159), [161](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L161), [161](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L161), [187](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L187), [211](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L211), [220](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L220), [223](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L223), [224](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L224), [228](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L228), [232](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L232), [254](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L254), [261](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L261), [262](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L262), [269](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L269), [276](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L276), [303](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L303), [310](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L310), [319](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L319), [329](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L329), [331](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L331)

```solidity
File: src/Root.sol

50:           emit File(what, data);

92:           emit RelyContract(target, user);

100:          emit DenyContract(target, user);

```
*GitHub*: [50](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L50), [92](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L92), [100](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L100)

```solidity
File: src/UserEscrow.sol

32:           SafeTransferLib.safeTransferFrom(token, source, address(this), amount);

33:           emit TransferIn(token, source, destination, amount);

43:               receiver == destination || (ERC20Like(token).allowance(destination, receiver) == type(uint256).max),

48:           SafeTransferLib.safeTransfer(token, receiver, amount);

49:           emit TransferOut(token, receiver, amount);

```
*GitHub*: [32](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L32), [32](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L32), [33](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L33), [33](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L33), [43](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L43), [48](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L48), [49](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L49)

```solidity
File: src/gateway/Gateway.sol

134:          emit File(what, data);

185:                  Messages.formatDomain(Messages.Domain.EVM, destinationChainId),

197:          outgoingRouter.send(Messages.formatTransfer(token, _addressToBytes32(sender), receiver, amount));

208:              Messages.formatIncreaseInvestOrder(poolId, trancheId, _addressToBytes32(investor), currency, currencyAmount)

220:              Messages.formatDecreaseInvestOrder(poolId, trancheId, _addressToBytes32(investor), currency, currencyAmount)

233:                  poolId, trancheId, _addressToBytes32(investor), currency, trancheTokenAmount

247:                  poolId, trancheId, _addressToBytes32(investor), currency, trancheTokenAmount

257:          outgoingRouter.send(Messages.formatCollectInvest(poolId, trancheId, _addressToBytes32(investor), currency));

265:          outgoingRouter.send(Messages.formatCollectRedeem(poolId, trancheId, _addressToBytes32(investor), currency));

273:          outgoingRouter.send(Messages.formatCancelInvestOrder(poolId, trancheId, _addressToBytes32(investor), currency));

281:          outgoingRouter.send(Messages.formatCancelRedeemOrder(poolId, trancheId, _addressToBytes32(investor), currency));

288:              poolManager.addCurrency(currency, currencyAddress);

294:              poolManager.allowPoolCurrency(poolId, currency);

304:              poolManager.addTranche(poolId, trancheId, tokenName, tokenSymbol, decimals);

307:              poolManager.updateMember(poolId, trancheId, user, validUntil);

311:              investmentManager.updateTrancheTokenPrice(poolId, trancheId, currencyId, price);

314:              poolManager.handleTransfer(currency, recipient, amount);

318:              poolManager.handleTransferTrancheTokens(poolId, trancheId, destinationAddress, amount);

322:              investmentManager.handleExecutedDecreaseInvestOrder(poolId, trancheId, investor, currency, currencyPayout);

327:                  poolId, trancheId, investor, currency, trancheTokensPayout

339:                  poolId, trancheId, investor, currency, currencyPayout, trancheTokensPayout

351:                  poolId, trancheId, investor, currency, currencyPayout, trancheTokensPayout

362:              poolManager.updateTrancheTokenMetadata(poolId, trancheId, tokenName, tokenSymbol);

```
*GitHub*: [134](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L134), [185](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L185), [197](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L197), [208](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L208), [208](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L208), [220](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L220), [220](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L220), [233](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L233), [233](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L233), [247](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L247), [247](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L247), [257](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L257), [257](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L257), [265](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L265), [265](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L265), [273](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L273), [273](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L273), [281](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L281), [281](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L281), [288](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L288), [294](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L294), [304](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L304), [304](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L304), [307](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L307), [307](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L307), [311](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L311), [311](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L311), [314](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L314), [318](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L318), [318](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L318), [322](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L322), [322](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L322), [327](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L327), [327](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L327), [339](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L339), [339](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L339), [351](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L351), [351](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L351), [362](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L362), [362](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L362)

```solidity
File: src/gateway/Messages.sol

69:           _call = Call(BytesLib.toUint8(_msg, 0));

80:           return abi.encodePacked(uint8(Call.AddCurrency), currency, currencyAddress);

88:           currency = BytesLib.toUint128(_msg, 1);

89:           currencyAddress = BytesLib.toAddress(_msg, 17);

99:           return abi.encodePacked(uint8(Call.AddPool), poolId);

107:          poolId = BytesLib.toUint64(_msg, 1);

118:          return abi.encodePacked(uint8(Call.AllowPoolCurrency), poolId, currency);

126:          poolId = BytesLib.toUint64(_msg, 1);

127:          currency = BytesLib.toUint128(_msg, 9);

179:          poolId = BytesLib.toUint64(_msg, 1);

180:          trancheId = BytesLib.toBytes16(_msg, 9);

181:          tokenName = _bytes128ToString(BytesLib.slice(_msg, 25, 128));

182:          tokenSymbol = _bytes32ToString(BytesLib.toBytes32(_msg, 153));

183:          decimals = BytesLib.toUint8(_msg, 185);

184:          price = BytesLib.toUint128(_msg, 186);

202:          return formatUpdateMember(poolId, trancheId, bytes32(bytes20(member)), validUntil);

210:          return abi.encodePacked(uint8(Call.UpdateMember), poolId, trancheId, member, validUntil);

222:          poolId = BytesLib.toUint64(_msg, 1);

223:          trancheId = BytesLib.toBytes16(_msg, 9);

224:          user = BytesLib.toAddress(_msg, 25);

225:          validUntil = BytesLib.toUint64(_msg, 57);

242:          return abi.encodePacked(uint8(Call.UpdateTrancheTokenPrice), poolId, trancheId, currencyId, price);

254:          poolId = BytesLib.toUint64(_msg, 1);

255:          trancheId = BytesLib.toBytes16(_msg, 9);

256:          currencyId = BytesLib.toUint128(_msg, 25);

257:          price = BytesLib.toUint128(_msg, 41);

274:          return abi.encodePacked(uint8(Call.Transfer), currency, sender, receiver, amount);

286:          currency = BytesLib.toUint128(_msg, 1);

287:          sender = BytesLib.toBytes32(_msg, 17);

288:          receiver = BytesLib.toBytes32(_msg, 49);

289:          amount = BytesLib.toUint128(_msg, 81);

299:          currency = BytesLib.toUint128(_msg, 1);

300:          recipient = BytesLib.toAddress(_msg, 49);

301:          amount = BytesLib.toUint128(_msg, 81);

324:              uint8(Call.TransferTrancheTokens), poolId, trancheId, sender, destinationDomain, destinationAddress, amount

341:              poolId, trancheId, sender, destinationDomain, bytes32(bytes20(destinationAddress)), amount

356:          poolId = BytesLib.toUint64(_msg, 1);

357:          trancheId = BytesLib.toBytes16(_msg, 9);

360:          destinationAddress = BytesLib.toAddress(_msg, 66);

361:          amount = BytesLib.toUint128(_msg, 98);

381:          return abi.encodePacked(uint8(Call.IncreaseInvestOrder), poolId, trancheId, investor, currency, amount);

393:          poolId = BytesLib.toUint64(_msg, 1);

394:          trancheId = BytesLib.toBytes16(_msg, 9);

395:          investor = BytesLib.toBytes32(_msg, 25);

396:          currency = BytesLib.toUint128(_msg, 57);

397:          amount = BytesLib.toUint128(_msg, 73);

417:          return abi.encodePacked(uint8(Call.DecreaseInvestOrder), poolId, trancheId, investor, currency, amount);

449:          return abi.encodePacked(uint8(Call.IncreaseRedeemOrder), poolId, trancheId, investor, currency, amount);

481:          return abi.encodePacked(uint8(Call.DecreaseRedeemOrder), poolId, trancheId, investor, currency, amount);

509:          return abi.encodePacked(uint8(Call.CollectInvest), poolId, trancheId, investor, currency);

521:          poolId = BytesLib.toUint64(_msg, 1);

522:          trancheId = BytesLib.toBytes16(_msg, 9);

523:          investor = BytesLib.toBytes32(_msg, 25);

524:          currency = BytesLib.toUint128(_msg, 57);

540:          return abi.encodePacked(uint8(Call.CollectRedeem), poolId, trancheId, investor, currency);

552:          poolId = BytesLib.toUint64(_msg, 1);

553:          trancheId = BytesLib.toBytes16(_msg, 9);

554:          investor = BytesLib.toBytes32(_msg, 25);

555:          currency = BytesLib.toUint128(_msg, 57);

566:              uint8(Call.ExecutedDecreaseInvestOrder), poolId, trancheId, investor, currency, currencyPayout

579:          poolId = BytesLib.toUint64(_msg, 1);

580:          trancheId = BytesLib.toBytes16(_msg, 9);

581:          investor = BytesLib.toAddress(_msg, 25);

582:          currency = BytesLib.toUint128(_msg, 57);

583:          trancheTokenPayout = BytesLib.toUint128(_msg, 73);

594:              uint8(Call.ExecutedDecreaseRedeemOrder), poolId, trancheId, investor, currency, trancheTokenPayout

607:          poolId = BytesLib.toUint64(_msg, 1);

608:          trancheId = BytesLib.toBytes16(_msg, 9);

609:          investor = BytesLib.toAddress(_msg, 25);

610:          currency = BytesLib.toUint128(_msg, 57);

611:          trancheTokensPayout = BytesLib.toUint128(_msg, 73);

649:          poolId = BytesLib.toUint64(_msg, 1);

650:          trancheId = BytesLib.toBytes16(_msg, 9);

651:          investor = BytesLib.toAddress(_msg, 25);

652:          currency = BytesLib.toUint128(_msg, 57);

653:          currencyPayout = BytesLib.toUint128(_msg, 73);

654:          trancheTokensPayout = BytesLib.toUint128(_msg, 89);

692:          poolId = BytesLib.toUint64(_msg, 1);

693:          trancheId = BytesLib.toBytes16(_msg, 9);

694:          investor = BytesLib.toAddress(_msg, 25);

695:          currency = BytesLib.toUint128(_msg, 57);

696:          currencyPayout = BytesLib.toUint128(_msg, 73);

697:          trancheTokensPayout = BytesLib.toUint128(_msg, 89);

709:          _contract = BytesLib.toAddress(_msg, 1);

721:          _contract = BytesLib.toAddress(_msg, 1);

760:          poolId = BytesLib.toUint64(_msg, 1);

761:          trancheId = BytesLib.toBytes16(_msg, 9);

762:          tokenName = _bytes128ToString(BytesLib.slice(_msg, 25, 128));

763:          tokenSymbol = _bytes32ToString(BytesLib.toBytes32(_msg, 153));

771:          return abi.encodePacked(uint8(Call.CancelInvestOrder), poolId, trancheId, investor, currency);

779:          poolId = BytesLib.toUint64(_msg, 1);

780:          trancheId = BytesLib.toBytes16(_msg, 9);

781:          investor = BytesLib.toAddress(_msg, 25);

782:          currency = BytesLib.toUint128(_msg, 57);

790:          return abi.encodePacked(uint8(Call.CancelRedeemOrder), poolId, trancheId, investor, currency);

798:          poolId = BytesLib.toUint64(_msg, 1);

799:          trancheId = BytesLib.toBytes16(_msg, 9);

800:          investor = BytesLib.toAddress(_msg, 25);

801:          currency = BytesLib.toUint128(_msg, 57);

817:          return abi.encodePacked(uint8(Call.UpdateTrancheInvestmentLimit), poolId, trancheId, investmentLimit);

829:          poolId = BytesLib.toUint64(_msg, 1);

830:          trancheId = BytesLib.toBytes16(_msg, 9);

831:          investmentLimit = BytesLib.toUint128(_msg, 25);

841:          return bytes9(BytesLib.slice(abi.encodePacked(uint8(domain), chainId), 0, 9));

883:              result := mload(add(source, 32))

```
*GitHub*: [69](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L69), [80](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L80), [88](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L88), [89](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L89), [99](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L99), [107](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L107), [118](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L118), [126](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L126), [127](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L127), [179](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L179), [180](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L180), [181](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L181), [182](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L182), [183](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L183), [184](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L184), [202](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L202), [202](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L202), [210](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L210), [210](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L210), [222](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L222), [223](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L223), [224](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L224), [225](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L225), [242](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L242), [242](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L242), [254](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L254), [255](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L255), [256](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L256), [257](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L257), [274](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L274), [274](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L274), [286](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L286), [287](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L287), [288](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L288), [289](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L289), [299](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L299), [300](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L300), [301](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L301), [324](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L324), [324](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L324), [324](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L324), [341](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L341), [341](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L341), [356](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L356), [357](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L357), [360](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L360), [361](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L361), [381](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L381), [381](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L381), [381](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L381), [393](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L393), [394](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L394), [395](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L395), [396](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L396), [397](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L397), [417](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L417), [417](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L417), [417](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L417), [449](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L449), [449](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L449), [449](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L449), [481](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L481), [481](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L481), [481](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L481), [509](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L509), [509](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L509), [521](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L521), [522](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L522), [523](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L523), [524](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L524), [540](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L540), [540](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L540), [552](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L552), [553](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L553), [554](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L554), [555](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L555), [566](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L566), [566](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L566), [579](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L579), [580](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L580), [581](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L581), [582](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L582), [583](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L583), [594](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L594), [594](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L594), [607](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L607), [608](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L608), [609](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L609), [610](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L610), [611](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L611), [649](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L649), [650](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L650), [651](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L651), [652](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L652), [653](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L653), [654](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L654), [692](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L692), [693](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L693), [694](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L694), [695](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L695), [696](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L696), [697](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L697), [709](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L709), [721](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L721), [760](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L760), [761](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L761), [762](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L762), [763](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L763), [771](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L771), [771](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L771), [779](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L779), [780](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L780), [781](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L781), [782](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L782), [790](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L790), [790](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L790), [798](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L798), [799](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L799), [800](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L800), [801](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L801), [817](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L817), [817](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L817), [829](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L829), [830](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L830), [831](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L831), [841](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L841), [841](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L841), [883](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L883)

```solidity
File: src/gateway/routers/axelar/Router.sol

69:           emit File(what, data);

78:       ) public onlyCentrifugeChainOrigin(sourceChain, sourceAddress) {

81:               axelarGateway.validateContractCall(commandId, sourceChain, sourceAddress, payloadHash),

90:           axelarGateway.callContract(axelarCentrifugeChainId, centrifugeGatewayPrecompileAddress, message);

```
*GitHub*: [69](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L69), [78](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L78), [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L81), [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L81), [90](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L90)

```solidity
File: src/token/ERC20.sol

2:    // Copyright (C) 2017, 2018, 2019 dbrock, rain, mrchico

87:           emit File(what, data);

101:          emit Transfer(_msgSender(), to, value);

126:          emit Transfer(from, to, value);

134:          emit Approval(_msgSender(), spender, value);

143:          emit Approval(_msgSender(), spender, newValue);

156:          emit Approval(_msgSender(), spender, allowed);

169:          emit Transfer(address(0), to, value);

192:          emit Transfer(from, address(0), value);

202:                  r := mload(add(signature, 0x20))

203:                  s := mload(add(signature, 0x40))

204:                  v := byte(0, mload(add(signature, 0x60)))

206:              if (signer == ecrecover(digest, v, r, s)) {

212:              signer.staticcall(abi.encodeWithSelector(IERC1271.isValidSignature.selector, digest, signature));

229:                  keccak256(abi.encode(PERMIT_TYPEHASH, owner, spender, value, nonce, deadline))

233:          require(_isValidSignature(owner, digest, signature), "ERC20/invalid-permit");

236:          emit Approval(owner, spender, value);

242:          permit(owner, spender, value, deadline, abi.encodePacked(r, s, v));

```
*GitHub*: [2](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L2), [2](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L2), [87](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L87), [101](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L101), [126](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L126), [134](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L134), [143](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L143), [156](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L156), [169](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L169), [192](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L192), [202](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L202), [203](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L203), [204](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L204), [206](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L206), [206](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L206), [212](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L212), [229](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L229), [229](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L229), [229](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L229), [233](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L233), [236](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L236), [242](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L242), [242](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L242), [242](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L242)

```solidity
File: src/token/RestrictionManager.sol

65:               updateMember(users[i], validUntil);

```
*GitHub*: [65](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L65)

```solidity
File: src/token/Tranche.sol

36:           uint8 restrictionCode = detectTransferRestriction(from, to, value);

45:           emit File(what, data);

59:       function transfer(address to, uint256 value) public override restricted(_msgSender(), to, value) returns (bool) {

60:           return super.transfer(to, value);

66:           restricted(from, to, value)

69:           return super.transferFrom(from, to, value);

72:       function mint(address to, uint256 value) public override restricted(_msgSender(), to, value) {

73:           return super.mint(to, value);

77:           return restrictionManager.detectTransferRestriction(from, to, value);

81:           return restrictionManager.detectTransferRestriction(from, to, value) == SUCCESS_CODE();

108:                  sender := shr(96, calldataload(sub(calldatasize(), 20)))

```
*GitHub*: [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L36), [45](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L45), [59](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L59), [60](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L60), [66](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L66), [69](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L69), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L72), [73](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L73), [77](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L77), [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L81), [108](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L108)

```solidity
File: src/util/Factory.sol

44:           LiquidityPool liquidityPool = new LiquidityPool(poolId, trancheId, currency, trancheToken, investmentManager);

94:           bytes32 salt = keccak256(abi.encodePacked(poolId, trancheId));

98:           token.file("name", name);

99:           token.file("symbol", symbol);

100:          token.file("restrictionManager", restrictionManager);

```
*GitHub*: [44](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L44), [44](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L44), [94](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L94), [98](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L98), [99](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L99), [100](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L100)

```solidity
File: src/util/SafeTransferLib.sol

17:               token.call(abi.encodeWithSelector(IERC20.transferFrom.selector, from, to, value));

27:           (bool success, bytes memory data) = token.call(abi.encodeWithSelector(IERC20.transfer.selector, to, value));

37:           (bool success, bytes memory data) = token.call(abi.encodeWithSelector(IERC20.approve.selector, to, value));

```
*GitHub*: [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L17), [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L17), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L27), [37](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L37)

</details>




### [N&#x2011;20] Top-level declarations should be separated by at least two lines
And functions within contracts should be separate by a [single](https://docs.soliditylang.org/en/latest/style-guide.html#blank-lines) line

*There are 146 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

172       }
173   
174:      function decreaseDepositRequest(uint256 _currencyAmount, address user) public auth {

185       }
186   
187:      function decreaseRedeemRequest(uint256 _trancheTokenAmount, address user) public auth {

198       }
199   
200:      function collectDeposit(address user) public auth {

209       }
210   
211:      function collectRedeem(address user) public auth {

232       }
233   
234:      function handleExecutedCollectInvest(

253       }
254   
255:      function handleExecutedCollectRedeem(

275       }
276   
277:      function handleExecutedDecreaseInvestOrder(

292       }
293   
294:      function handleExecutedDecreaseRedeemOrder(

465       }
466   
467:      function _deposit(uint128 trancheTokenAmount, uint128 currencyAmount, address liquidityPool, address user)

533       }
534   
535:      function _redeem(

558       }
559   
560:      function calculateRedeemPrice(address user, address liquidityPool) public view returns (uint256 redeemPrice) {

567       }
568   
569:      function _calculatePrice(uint128 currencyAmount, uint128 trancheTokenAmount, address liquidityPool)

582       }
583   
584:      function _updateLiquidityPoolPrice(address liquidityPool, uint128 currencyPayout, uint128 trancheTokensPayout)

589       }
590   
591:      function _calculateTrancheTokenAmount(uint128 currencyAmount, address liquidityPool, uint256 price)

603       }
604   
605:      function _calculateCurrencyAmount(uint128 trancheTokenAmount, address liquidityPool, uint256 price)

617       }
618   
619:      function _decreaseDepositLimits(address user, address liquidityPool, uint128 _currency, uint128 trancheTokens)

633       }
634   
635:      function _decreaseRedemptionLimits(address user, address liquidityPool, uint128 _currency, uint128 trancheTokens)

649       }
650   
651:      function _isAllowedToInvest(uint64 poolId, bytes16 trancheId, address currency, address user)

```
*GitHub*: [172](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L172-L174), [185](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L185-L187), [198](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L198-L200), [209](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L209-L211), [232](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L232-L234), [253](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L253-L255), [275](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L275-L277), [292](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L292-L294), [465](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L465-L467), [533](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L533-L535), [558](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L558-L560), [567](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L567-L569), [582](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L582-L584), [589](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L589-L591), [603](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L603-L605), [617](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L617-L619), [633](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L633-L635), [649](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L649-L651)

```solidity
File: src/LiquidityPool.sol

273       }
274   
275:      function symbol() public view returns (string memory) {

277       }
278   
279:      function decimals() public view returns (uint8) {

281       }
282   
283:      function totalSupply() public view returns (uint256) {

285       }
286   
287:      function balanceOf(address owner) public view returns (uint256) {

289       }
290   
291:      function allowance(address owner, address spender) public view returns (uint256) {

293       }
294   
295:      function transferFrom(address, address, uint256) public returns (bool) {

299       }
300   
301:      function transfer(address, uint256) public returns (bool) {

305       }
306   
307:      function approve(address, uint256) public returns (bool) {

311       }
312   
313:      function mint(address, uint256) public auth {

316       }
317   
318:      function burn(address, uint256) public auth {

```
*GitHub*: [273](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L273-L275), [277](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L277-L279), [281](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L281-L283), [285](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L285-L287), [289](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L289-L291), [293](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L293-L295), [299](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L299-L301), [305](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L305-L307), [311](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L311-L313), [316](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L316-L318)

```solidity
File: src/PoolManager.sol

134       }
135   
136:      function transferTrancheTokensToCentrifuge(

147       }
148   
149:      function transferTrancheTokensToEVM(

212       }
213   
214:      function updateTrancheTokenMetadata(

225       }
226   
227:      function updateMember(uint64 poolId, bytes16 trancheId, address user, uint64 validUntil) public onlyGateway {

255       }
256   
257:      function handleTransfer(uint128 currency, address recipient, uint128 amount) public onlyGateway {

263       }
264   
265:      function handleTransferTrancheTokens(uint64 poolId, bytes16 trancheId, address destinationAddress, uint128 amount)

305       }
306   
307:      function deployLiquidityPool(uint64 poolId, bytes16 trancheId, address currency) public returns (address) {

339       }
340   
341:      function getLiquidityPool(uint64 poolId, bytes16 trancheId, address currency) public view returns (address) {

343       }
344   
345:      function isAllowedAsPoolCurrency(uint64 poolId, address currencyAddress) public view returns (bool) {

```
*GitHub*: [134](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L134-L136), [147](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L147-L149), [212](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L212-L214), [225](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L225-L227), [255](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L255-L257), [263](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L263-L265), [305](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L305-L307), [339](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L339-L341), [343](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L343-L345)

```solidity
File: src/Root.sol

83        }
84    
85:       /// --- External contract ward management ---

57        }
58    
59:       function unpause() external auth {

68        }
69    
70:       function cancelRely(address target) external auth {

73        }
74    
75:       function executeScheduledRely(address target) public {

```
*GitHub*: [83](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L83-L85), [57](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L57-L59), [68](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L68-L70), [73](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L73-L75)

```solidity
File: src/UserEscrow.sol

34        }
35    
36:       function transferOut(address token, address destination, address receiver, uint256 amount) external auth {

```
*GitHub*: [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L34-L36)

```solidity
File: src/admins/DelayedAdmin.sol

28        }
29    
30:       function unpause() public auth {

32        }
33    
34:       function scheduleRely(address target) public auth {

36        }
37    
38:       function cancelRely(address target) public auth {

```
*GitHub*: [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L28-L30), [32](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L32-L34), [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L36-L38)

```solidity
File: src/admins/PauseAdmin.sol

37        }
38    
39:       function removePauser(address user) external auth {

```
*GitHub*: [37](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L37-L39)

```solidity
File: src/gateway/Gateway.sol

135       }
136   
137:      function addIncomingRouter(address router) public auth {

140       }
141   
142:      function removeIncomingRouter(address router) public auth {

145       }
146   
147:      function updateOutgoingRouter(address router) public auth {

170       }
171   
172:      function transferTrancheTokensToEVM(

190       }
191   
192:      function transfer(uint128 token, address sender, bytes32 receiver, uint128 amount)

198       }
199   
200:      function increaseInvestOrder(

210       }
211   
212:      function decreaseInvestOrder(

222       }
223   
224:      function increaseRedeemOrder(

236       }
237   
238:      function decreaseRedeemOrder(

250       }
251   
252:      function collectInvest(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)

258       }
259   
260:      function collectRedeem(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)

266       }
267   
268:      function cancelInvestOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)

274       }
275   
276:      function cancelRedeemOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)

```
*GitHub*: [135](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L135-L137), [140](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L140-L142), [145](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L145-L147), [170](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L170-L172), [190](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L190-L192), [198](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L198-L200), [210](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L210-L212), [222](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L222-L224), [236](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L236-L238), [250](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L250-L252), [258](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L258-L260), [266](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L266-L268), [274](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L274-L276)

```solidity
File: src/gateway/Messages.sol

66        }
67    
68:       function messageType(bytes memory _msg) internal pure returns (Call _call) {

81        }
82    
83:       function isAddCurrency(bytes memory _msg) internal pure returns (bool) {

85        }
86    
87:       function parseAddCurrency(bytes memory _msg) internal pure returns (uint128 currency, address currencyAddress) {

100       }
101   
102:      function isAddPool(bytes memory _msg) internal pure returns (bool) {

104       }
105   
106:      function parseAddPool(bytes memory _msg) internal pure returns (uint64 poolId) {

119       }
120   
121:      function isAllowPoolCurrency(bytes memory _msg) internal pure returns (bool) {

123       }
124   
125:      function parseAllowPoolCurrency(bytes memory _msg) internal pure returns (uint64 poolId, uint128 currency) {

161       }
162   
163:      function isAddTranche(bytes memory _msg) internal pure returns (bool) {

165       }
166   
167:      function parseAddTranche(bytes memory _msg)

203       }
204   
205:      function formatUpdateMember(uint64 poolId, bytes16 trancheId, bytes32 member, uint64 validUntil)

211       }
212   
213:      function isUpdateMember(bytes memory _msg) internal pure returns (bool) {

215       }
216   
217:      function parseUpdateMember(bytes memory _msg)

243       }
244   
245:      function isUpdateTrancheTokenPrice(bytes memory _msg) internal pure returns (bool) {

247       }
248   
249:      function parseUpdateTrancheTokenPrice(bytes memory _msg)

275       }
276   
277:      function isTransfer(bytes memory _msg) internal pure returns (bool) {

279       }
280   
281:      function parseTransfer(bytes memory _msg)

343       }
344   
345:      function isTransferTrancheTokens(bytes memory _msg) internal pure returns (bool) {

382       }
383   
384:      function isIncreaseInvestOrder(bytes memory _msg) internal pure returns (bool) {

386       }
387   
388:      function parseIncreaseInvestOrder(bytes memory _msg)

418       }
419   
420:      function isDecreaseInvestOrder(bytes memory _msg) internal pure returns (bool) {

422       }
423   
424:      function parseDecreaseInvestOrder(bytes memory _msg)

450       }
451   
452:      function isIncreaseRedeemOrder(bytes memory _msg) internal pure returns (bool) {

454       }
455   
456:      function parseIncreaseRedeemOrder(bytes memory _msg)

482       }
483   
484:      function isDecreaseRedeemOrder(bytes memory _msg) internal pure returns (bool) {

486       }
487   
488:      function parseDecreaseRedeemOrder(bytes memory _msg)

510       }
511   
512:      function isCollectInvest(bytes memory _msg) internal pure returns (bool) {

514       }
515   
516:      function parseCollectInvest(bytes memory _msg)

541       }
542   
543:      function isCollectRedeem(bytes memory _msg) internal pure returns (bool) {

545       }
546   
547:      function parseCollectRedeem(bytes memory _msg)

556       }
557   
558:      function formatExecutedDecreaseInvestOrder(

568       }
569   
570:      function isExecutedDecreaseInvestOrder(bytes memory _msg) internal pure returns (bool) {

572       }
573   
574:      function parseExecutedDecreaseInvestOrder(bytes memory _msg)

584       }
585   
586:      function formatExecutedDecreaseRedeemOrder(

596       }
597   
598:      function isExecutedDecreaseRedeemOrder(bytes memory _msg) internal pure returns (bool) {

600       }
601   
602:      function parseExecutedDecreaseRedeemOrder(bytes memory _msg)

612       }
613   
614:      function formatExecutedCollectInvest(

631       }
632   
633:      function isExecutedCollectInvest(bytes memory _msg) internal pure returns (bool) {

635       }
636   
637:      function parseExecutedCollectInvest(bytes memory _msg)

655       }
656   
657:      function formatExecutedCollectRedeem(

674       }
675   
676:      function isExecutedCollectRedeem(bytes memory _msg) internal pure returns (bool) {

678       }
679   
680:      function parseExecutedCollectRedeem(bytes memory _msg)

698       }
699   
700:      function formatScheduleUpgrade(address _contract) internal pure returns (bytes memory) {

702       }
703   
704:      function isScheduleUpgrade(bytes memory _msg) internal pure returns (bool) {

706       }
707   
708:      function parseScheduleUpgrade(bytes memory _msg) internal pure returns (address _contract) {

710       }
711   
712:      function formatCancelUpgrade(address _contract) internal pure returns (bytes memory) {

714       }
715   
716:      function isCancelUpgrade(bytes memory _msg) internal pure returns (bool) {

718       }
719   
720:      function parseCancelUpgrade(bytes memory _msg) internal pure returns (address _contract) {

749       }
750   
751:      function isUpdateTrancheTokenMetadata(bytes memory _msg) internal pure returns (bool) {

753       }
754   
755:      function parseUpdateTrancheTokenMetadata(bytes memory _msg)

764       }
765   
766:      function formatCancelInvestOrder(uint64 poolId, bytes16 trancheId, bytes32 investor, uint128 currency)

772       }
773   
774:      function parseCancelInvestOrder(bytes memory _msg)

783       }
784   
785:      function formatCancelRedeemOrder(uint64 poolId, bytes16 trancheId, bytes32 investor, uint128 currency)

791       }
792   
793:      function parseCancelRedeemOrder(bytes memory _msg)

818       }
819   
820:      function isUpdateTrancheInvestmentLimit(bytes memory _msg) internal pure returns (bool) {

822       }
823   
824:      function parseUpdateTrancheInvestmentLimit(bytes memory _msg)

838       }
839   
840:      function formatDomain(Domain domain, uint64 chainId) public pure returns (bytes9) {

842       }
843   
844:      function _stringToBytes128(string memory source) internal pure returns (bytes memory) {

857       }
858   
859:      function _bytes128ToString(bytes memory _bytes128) internal pure returns (string memory) {

874       }
875   
876:      function _stringToBytes32(string memory source) internal pure returns (bytes32 result) {

885       }
886   
887:      function _bytes32ToString(bytes32 _bytes32) internal pure returns (string memory) {

```
*GitHub*: [66](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L66-L68), [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L81-L83), [85](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L85-L87), [100](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L100-L102), [104](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L104-L106), [119](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L119-L121), [123](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L123-L125), [161](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L161-L163), [165](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L165-L167), [203](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L203-L205), [211](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L211-L213), [215](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L215-L217), [243](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L243-L245), [247](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L247-L249), [275](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L275-L277), [279](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L279-L281), [343](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L343-L345), [382](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L382-L384), [386](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L386-L388), [418](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L418-L420), [422](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L422-L424), [450](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L450-L452), [454](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L454-L456), [482](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L482-L484), [486](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L486-L488), [510](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L510-L512), [514](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L514-L516), [541](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L541-L543), [545](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L545-L547), [556](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L556-L558), [568](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L568-L570), [572](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L572-L574), [584](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L584-L586), [596](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L596-L598), [600](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L600-L602), [612](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L612-L614), [631](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L631-L633), [635](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L635-L637), [655](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L655-L657), [674](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L674-L676), [678](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L678-L680), [698](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L698-L700), [702](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L702-L704), [706](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L706-L708), [710](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L710-L712), [714](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L714-L716), [718](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L718-L720), [749](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L749-L751), [753](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L753-L755), [764](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L764-L766), [772](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L772-L774), [783](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L783-L785), [791](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L791-L793), [818](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L818-L820), [822](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L822-L824), [838](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L838-L840), [842](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L842-L844), [857](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L857-L859), [874](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L874-L876), [885](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L885-L887)

```solidity
File: src/token/ERC20.sol

55        }
56    
57:       function rely(address user) external auth {

60        }
61    
62:       function deny(address user) external auth {

65        }
66    
67:       function _calculateDomainSeparator(uint256 chainId) private view returns (bytes32) {

77        }
78    
79:       function DOMAIN_SEPARATOR() external view returns (bytes32) {

81        }
82    
83:       function file(bytes32 what, string memory data) external auth {

104       }
105   
106:      function transferFrom(address from, address to, uint256 value) public virtual returns (bool) {

129       }
130   
131:      function approve(address spender, uint256 value) external returns (bool) {

137       }
138   
139:      function increaseAllowance(address spender, uint256 addedValue) external returns (bool) {

146       }
147   
148:      function decreaseAllowance(address spender, uint256 subtractedValue) external returns (bool) {

170       }
171   
172:      function burn(address from, uint256 value) external auth {

214       }
215   
216:      function permit(address owner, address spender, uint256 value, uint256 deadline, bytes memory signature) public {

237       }
238   
239:      function permit(address owner, address spender, uint256 value, uint256 deadline, uint8 v, bytes32 r, bytes32 s)

```
*GitHub*: [55](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L55-L57), [60](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L60-L62), [65](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L65-L67), [77](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L77-L79), [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L81-L83), [104](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L104-L106), [129](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L129-L131), [137](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L137-L139), [146](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L146-L148), [170](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L170-L172), [214](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L214-L216), [237](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L237-L239)

```solidity
File: src/token/RestrictionManager.sol

34        }
35    
36:       function messageForTransferRestriction(uint8 restrictionCode) public view returns (string memory) {

47        }
48    
49:       function hasMember(address user) public view returns (bool) {

60        }
61    
62:       function updateMembers(address[] memory users, uint256 validUntil) public auth {

```
*GitHub*: [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L34-L36), [47](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L47-L49), [60](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L60-L62)

```solidity
File: src/token/Tranche.sol

46        }
47    
48:       function addLiquidityPool(address liquidityPool) public auth {

51        }
52    
53:       function removeLiquidityPool(address liquidityPool) public auth {

61        }
62    
63:       function transferFrom(address from, address to, uint256 value)

70        }
71    
72:       function mint(address to, uint256 value) public override restricted(_msgSender(), to, value) {

74        }
75    
76:       function detectTransferRestriction(address from, address to, uint256 value) public view returns (uint8) {

78        }
79    
80:       function checkTransferRestriction(address from, address to, uint256 value) public view returns (bool) {

82        }
83    
84:       function messageForTransferRestriction(uint8 restrictionCode) public view returns (string memory) {

86        }
87    
88:       function SUCCESS_CODE() public view returns (uint8) {

```
*GitHub*: [46](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L46-L48), [51](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L51-L53), [61](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L61-L63), [70](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L70-L72), [74](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L74-L76), [78](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L78-L80), [82](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L82-L84), [86](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L86-L88)

```solidity
File: src/util/Factory.sol

34        }
35    
36:       function newLiquidityPool(

79        }
80    
81:       function newTrancheToken(

109       }
110   
111:      function _newRestrictionManager(address[] calldata restrictionManagerWards) internal returns (address memberList) {

```
*GitHub*: [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L34-L36), [79](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L79-L81), [109](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L109-L111)

```solidity
File: src/util/SafeTransferLib.sol

29        }
30    
31:       /// @notice Approves the stipulated contract to spend the given allowance in the given token

```
*GitHub*: [29](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L29-L31)

</details>




### [N&#x2011;21] Consider using `delete` rather than assigning zero/false to clear values
The `delete` keyword more closely matches the semantics of what is being done, and draws more attention to the changing of state, which may lead to a more thorough audit of its associated logic

*There are 11 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

624:              lpValues.maxDeposit = 0;

629:              lpValues.maxMint = 0;

640:              lpValues.maxWithdraw = 0;

645:              lpValues.maxRedeem = 0;

```
*GitHub*: [624](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L624), [629](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L629), [640](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L640), [645](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L645)

```solidity
File: src/Root.sol

71:           schedule[target] = 0;

82:           schedule[target] = 0;

```
*GitHub*: [71](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L71), [82](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L82)

```solidity
File: src/admins/PauseAdmin.sol

40:           pausers[user] = 0;

```
*GitHub*: [40](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L40)

```solidity
File: src/gateway/Gateway.sol

143:          incomingRouters[router] = false;

```
*GitHub*: [143](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L143)

```solidity
File: src/token/ERC20.sol

63:           wards[user] = 0;

```
*GitHub*: [63](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L63)

```solidity
File: src/token/Tranche.sol

54:           liquidityPools[liquidityPool] = false;

```
*GitHub*: [54](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L54)

```solidity
File: src/util/Auth.sol

21:           wards[user] = 0;

```
*GitHub*: [21](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L21)

</details>




### [N&#x2011;22] Contracts should have full test coverage
While 100% code coverage does not guarantee that there are no bugs, it often will catch easy-to-find bugs, and will ensure that there are fewer regressions when the code invariably has to be modified. Furthermore, in order to get full coverage, code authors will often have to re-organize their code so that it is more modular, so that each component can be tested separately, which reduces interdependencies between modules and layers, and makes for code that is easier to reason about and audit.

*There is one instance of this issue:*

```solidity
File: Various Files


```


### [N&#x2011;23] Large or complicated code bases should implement invariant tests
Large code bases, or code with lots of inline-assembly, complicated math, or complicated interactions between multiple contracts, should implement [invariant fuzzing tests](https://medium.com/coinmonks/smart-contract-fuzzing-d9b88e0b0a05). Invariant fuzzers such as Echidna require the test writer to come up with invariants which should not be violated under any circumstances, and the fuzzer tests various inputs and function calls to ensure that the invariants always hold. Even code with 100% code coverage can still have bugs due to the order of the operations a user performs, and invariant fuzzers, with properly and extensively-written invariants, can close this testing gap significantly.

*There is one instance of this issue:*

```solidity
File: Various Files


```


### [N&#x2011;24] Consider adding formal verification proofs
Consider using formal verification to mathematically prove that your code does what is intended, and does not have any edge cases with unexpected behavior. The solidity compiler itself has this functionality [built in](https://docs.soliditylang.org/en/latest/smtchecker.html#smtchecker-and-formal-verification)

*There is one instance of this issue:*

```solidity
File: Various Files


```


### [N&#x2011;25] Multiple `address`/ID mappings can be combined into a single `mapping` of an `address`/ID to a `struct`, for readability
Well-organized data structures make code reviews easier, which may lead to fewer bugs. Consider combining related mappings into mappings to structs, so it's clear what data is related

*There is one instance of this issue:*

```solidity
File: src/token/ERC20.sol

25        mapping(address => uint256) public balanceOf;
26        mapping(address => mapping(address => uint256)) public allowance;
27:       mapping(address => uint256) public nonces;

```
*GitHub*: [25](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L25-L27)


### [N&#x2011;26] Custom errors should be used rather than `revert()`/`require()`
Custom errors are available from solidity version 0.8.4. Custom errors are more easily processed in `try`-`catch` blocks, and are easier to re-use and maintain.

*There are 92 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

98:           require(msg.sender == address(gateway), "InvestmentManager/not-the-gateway");

177:          require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

190:          require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

202:          require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

213:          require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

229:          require(liquidityPool != address(0), "InvestmentManager/tranche-does-not-exist");

242:          require(currencyPayout != 0, "InvestmentManager/zero-invest");

245:          require(liquidityPool != address(0), "InvestmentManager/tranche-does-not-exist");

263:          require(trancheTokensPayout != 0, "InvestmentManager/zero-redeem");

266:          require(liquidityPool != address(0), "InvestmentManager/tranche-does-not-exist");

284:          require(currencyPayout != 0, "InvestmentManager/zero-payout");

288:          require(liquidityPool != address(0), "InvestmentManager/tranche-does-not-exist");

289:          require(_currency == LiquidityPoolLike(liquidityPool).asset(), "InvestmentManager/not-tranche-currency");

301:          require(trancheTokenPayout != 0, "InvestmentManager/zero-payout");

305:          require(address(liquidityPool) != address(0), "InvestmentManager/tranche-does-not-exist");

307           require(
308               LiquidityPoolLike(liquidityPool).checkTransferRestriction(address(0), user, 0),
309               "InvestmentManager/not-a-member"
310:          );

312           require(
313               LiquidityPoolLike(liquidityPool).transferFrom(address(escrow), user, trancheTokenPayout),
314               "InvestmentManager/trancheTokens-transfer-failed"
315:          );

430           require(
431               (_currencyAmount <= orderbook[user][liquidityPool].maxDeposit && _currencyAmount != 0),
432               "InvestmentManager/amount-exceeds-deposit-limits"
433:          );

436:          require(depositPrice != 0, "LiquidityPool/deposit-token-price-0");

454           require(
455               (_trancheTokenAmount <= orderbook[user][liquidityPool].maxMint && _trancheTokenAmount != 0),
456               "InvestmentManager/amount-exceeds-mint-limits"
457:          );

460:          require(depositPrice != 0, "LiquidityPool/deposit-token-price-0");

473:          require(lPool.checkTransferRestriction(msg.sender, user, 0), "InvestmentManager/trancheTokens-not-a-member");

474           require(
475               lPool.transferFrom(address(escrow), user, trancheTokenAmount),
476               "InvestmentManager/trancheTokens-transfer-failed"
477:          );

496           require(
497               (_trancheTokenAmount <= orderbook[user][liquidityPool].maxRedeem && _trancheTokenAmount != 0),
498               "InvestmentManager/amount-exceeds-redeem-limits"
499:          );

502:          require(redeemPrice != 0, "LiquidityPool/redeem-token-price-0");

522           require(
523               (_currencyAmount <= orderbook[user][liquidityPool].maxWithdraw && _currencyAmount != 0),
524               "InvestmentManager/amount-exceeds-withdraw-limits"
525:          );

528:          require(redeemPrice != 0, "LiquidityPool/redeem-token-price-0");

656:          require(liquidityPool != address(0), "InvestmentManager/unknown-liquidity-pool");

657           require(
658               LiquidityPoolLike(liquidityPool).checkTransferRestriction(address(0), user, 0),
659               "InvestmentManager/not-a-member"
660:          );

```
*GitHub*: [98](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L98), [177](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L177), [190](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L190), [202](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L202), [213](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L213), [229](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L229), [242](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L242), [245](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L245), [263](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L263), [266](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L266), [284](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L284), [288](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L288), [289](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L289), [301](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L301), [305](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L305), [307](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L307-L310), [312](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L312-L315), [430](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L430-L433), [436](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L436), [454](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L454-L457), [460](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L460), [473](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L473), [474](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L474-L477), [496](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L496-L499), [502](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L502), [522](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L522-L525), [528](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L528), [656](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L656), [657](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L657-L660)

```solidity
File: src/LiquidityPool.sol

98:           require(msg.sender == owner, "LiquidityPool/no-approval");

```
*GitHub*: [98](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L98)

```solidity
File: src/PoolManager.sol

115:          require(msg.sender == address(gateway), "PoolManager/not-the-gateway");

130:          require(currency != 0, "PoolManager/unknown-currency");

143:          require(address(trancheToken) != address(0), "PoolManager/unknown-token");

157:          require(address(trancheToken) != address(0), "PoolManager/unknown-token");

170:          require(pool.createdAt == 0, "PoolManager/pool-already-added");

181:          require(pool.createdAt != 0, "PoolManager/invalid-pool");

184:          require(currencyAddress != address(0), "PoolManager/unknown-currency");

200:          require(pool.createdAt != 0, "PoolManager/invalid-pool");

202:          require(tranche.createdAt == 0, "PoolManager/tranche-already-exists");

221:          require(address(trancheToken) != address(0), "PoolManager/unknown-token");

229:          require(address(trancheToken) != address(0), "PoolManager/unknown-token");

240:          require(currency != 0, "PoolManager/currency-id-has-to-be-greater-than-0");

241:          require(currencyIdToAddress[currency] == address(0), "PoolManager/currency-id-in-use");

242:          require(currencyAddressToId[currencyAddress] == 0, "PoolManager/currency-address-in-use");

243:          require(IERC20(currencyAddress).decimals() <= MAX_CURRENCY_DECIMALS, "PoolManager/too-many-currency-decimals");

259:          require(currencyAddress != address(0), "PoolManager/unknown-currency");

270:          require(address(trancheToken) != address(0), "PoolManager/unknown-token");

272           require(
273               MemberlistLike(address(trancheToken.restrictionManager())).hasMember(destinationAddress),
274               "PoolManager/not-a-member"
275:          );

282:          require(tranche.token == address(0), "PoolManager/tranche-already-deployed");

283:          require(tranche.createdAt != 0, "PoolManager/tranche-not-added");

309:          require(tranche.token != address(0), "PoolManager/tranche-does-not-exist"); // Tranche must have been added

310:          require(isAllowedAsPoolCurrency(poolId, currency), "PoolManager/currency-not-supported"); // Currency must be supported by pool

313:          require(liquidityPool == address(0), "PoolManager/liquidityPool-already-deployed");

314:          require(pools[poolId].createdAt != 0, "PoolManager/pool-does-not-exist");

347:          require(currency != 0, "PoolManager/unknown-currency"); // Currency index on the Centrifuge side should start at 1

348:          require(pools[poolId].allowedCurrencies[currencyAddress], "PoolManager/pool-currency-not-allowed");

```
*GitHub*: [115](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L115), [130](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L130), [143](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L143), [157](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L157), [170](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L170), [181](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L181), [184](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L184), [200](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L200), [202](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L202), [221](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L221), [229](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L229), [240](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L240), [241](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L241), [242](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L242), [243](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L243), [259](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L259), [270](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L270), [272](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L272-L275), [282](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L282), [283](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L283), [309](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L309), [310](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L310), [313](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L313), [314](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L314), [347](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L347), [348](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L348)

```solidity
File: src/Root.sol

45:               require(data <= MAX_DELAY, "Root/delay-too-long");

76:           require(schedule[target] != 0, "Root/target-not-scheduled");

77:           require(schedule[target] < block.timestamp, "Root/target-not-ready");

```
*GitHub*: [45](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L45), [76](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L76), [77](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L77)

```solidity
File: src/UserEscrow.sol

37:           require(destinations[token][destination] >= amount, "UserEscrow/transfer-failed");

38            require(
39                /// @dev transferOut can only be initiated by the destination address or an authorized admin.
40                ///      The check is just an additional protection to secure destination funds in case of compromized auth.
41                ///      Since userEscrow is not able to decrease the allowance for the receiver,
42                ///      a transfer is only possible in case receiver has received the full allowance from destination address.
43                receiver == destination || (ERC20Like(token).allowance(destination, receiver) == type(uint256).max),
44                "UserEscrow/receiver-has-no-allowance"
45:           );

```
*GitHub*: [37](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L37), [38](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L38-L45)

```solidity
File: src/admins/PauseAdmin.sol

29:           require(pausers[msg.sender] == 1, "PauseAdmin/not-authorized-to-pause");

```
*GitHub*: [29](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L29)

```solidity
File: src/gateway/Gateway.sol

110:          require(msg.sender == address(investmentManager), "Gateway/only-investment-manager-allowed-to-call");

115:          require(msg.sender == address(poolManager), "Gateway/only-pool-manager-allowed-to-call");

120:          require(incomingRouters[msg.sender], "Gateway/only-router-allowed-to-call");

125:          require(!root.paused(), "Gateway/paused");

```
*GitHub*: [110](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L110), [115](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L115), [120](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L120), [125](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L125)

```solidity
File: src/gateway/Messages.sol

860:          require(_bytes128.length == 128, "Input should be 128 bytes");

```
*GitHub*: [860](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L860)

```solidity
File: src/gateway/routers/axelar/Router.sol

44:           require(msg.sender == address(axelarGateway), "AxelarRouter/invalid-origin");

45            require(
46                keccak256(bytes(axelarCentrifugeChainId)) == keccak256(bytes(sourceChain)),
47                "AxelarRouter/invalid-source-chain"
48:           );

49            require(
50                keccak256(bytes(axelarCentrifugeChainAddress)) == keccak256(bytes(sourceAddress)),
51                "AxelarRouter/invalid-source-address"
52:           );

57:           require(msg.sender == address(gateway), "AxelarRouter/only-gateway-allowed-to-call");

80            require(
81                axelarGateway.validateContractCall(commandId, sourceChain, sourceAddress, payloadHash),
82                "Router/not-approved-by-gateway"
83:           );

```
*GitHub*: [44](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L44), [45](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L45-L48), [49](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L49-L52), [57](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L57), [80](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L80-L83)

```solidity
File: src/token/ERC20.sol

53:           require(wards[_msgSender()] == 1, "Auth/not-authorized");

92:           require(to != address(0) && to != address(this), "ERC20/invalid-address");

94:           require(balance >= value, "ERC20/insufficient-balance");

107:          require(to != address(0) && to != address(this), "ERC20/invalid-address");

109:          require(balance >= value, "ERC20/insufficient-balance");

114:                  require(allowed >= value, "ERC20/insufficient-allowance");

150:          require(allowed >= subtractedValue, "ERC20/insufficient-allowance");

163:          require(to != address(0) && to != address(this), "ERC20/invalid-address");

174:          require(balance >= value, "ERC20/insufficient-balance");

179:                  require(allowed >= value, "ERC20/insufficient-allowance");

217:          require(block.timestamp <= deadline, "ERC20/permit-expired");

218:          require(owner != address(0), "ERC20/invalid-owner");

233:          require(_isValidSignature(owner, digest, signature), "ERC20/invalid-permit");

```
*GitHub*: [53](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L53), [92](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L92), [94](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L94), [107](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L107), [109](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L109), [114](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L114), [150](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L150), [163](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L163), [174](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L174), [179](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L179), [217](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L217), [218](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L218), [233](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L233)

```solidity
File: src/token/RestrictionManager.sol

46:           require((members[user] >= block.timestamp), "RestrictionManager/destination-not-a-member");

58:           require(block.timestamp <= validUntil, "RestrictionManager/invalid-valid-until");

```
*GitHub*: [46](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L46), [58](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L58)

```solidity
File: src/token/Tranche.sol

37:           require(restrictionCode == restrictionManager.SUCCESS_CODE(), messageForTransferRestriction(restrictionCode));

```
*GitHub*: [37](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L37)

```solidity
File: src/util/Auth.sol

27:           require(wards[msg.sender] == 1, "Auth/not-authorized");

```
*GitHub*: [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L27)

```solidity
File: src/util/SafeTransferLib.sol

18:           require(success && (data.length == 0 || abi.decode(data, (bool))), "SafeTransferLib/safe-transfer-from-failed");

28:           require(success && (data.length == 0 || abi.decode(data, (bool))), "SafeTransferLib/safe-transfer-failed");

38:           require(success && (data.length == 0 || abi.decode(data, (bool))), "SafeTransferLib/safe-approve-failed");

```
*GitHub*: [18](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L18), [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L28), [38](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L38)

</details>




### [N&#x2011;27] Not using the named return variables anywhere in the function is confusing
Consider changing the variable to be an unnamed one, since the variable is never assigned, nor is it returned by name. If the optimizer is not turned on, leaving the code as it is will also waste gas for the stack variable.

*There are 20 instances of this issue:*

```solidity
File: src/LiquidityPool.sol

/// @audit maxAssets
165:      function maxWithdraw(address receiver) public view returns (uint256 maxAssets) {

/// @audit shares
176       function withdraw(uint256 assets, address receiver, address owner)
177           public
178           withApproval(owner)
179:          returns (uint256 shares)

/// @audit maxShares
187:      function maxRedeem(address owner) public view returns (uint256 maxShares) {

/// @audit assets
200       function redeem(uint256 shares, address receiver, address owner)
201           public
202           withApproval(owner)
203:          returns (uint256 assets)

```
*GitHub*: [165](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L165), [176](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L176-L179), [187](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L187), [200](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L200-L203)

```solidity
File: src/gateway/Messages.sol

/// @audit poolId
/// @audit trancheId
/// @audit investor
/// @audit currency
/// @audit amount
424       function parseDecreaseInvestOrder(bytes memory _msg)
425           internal
426           pure
427:          returns (uint64 poolId, bytes16 trancheId, bytes32 investor, uint128 currency, uint128 amount)

/// @audit poolId
/// @audit trancheId
/// @audit investor
/// @audit currency
/// @audit amount
456       function parseIncreaseRedeemOrder(bytes memory _msg)
457           internal
458           pure
459:          returns (uint64 poolId, bytes16 trancheId, bytes32 investor, uint128 currency, uint128 amount)

/// @audit poolId
/// @audit trancheId
/// @audit investor
/// @audit currency
/// @audit amount
488       function parseDecreaseRedeemOrder(bytes memory _msg)
489           internal
490           pure
491:          returns (uint64 poolId, bytes16 trancheId, bytes32 investor, uint128 currency, uint128 amount)

```
*GitHub*: [424](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L424-L427), [424](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L424-L427), [424](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L424-L427), [424](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L424-L427), [424](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L424-L427), [456](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L456-L459), [456](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L456-L459), [456](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L456-L459), [456](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L456-L459), [456](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L456-L459), [488](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L488-L491), [488](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L488-L491), [488](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L488-L491), [488](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L488-L491), [488](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L488-L491)

```solidity
File: src/util/Factory.sol

/// @audit memberList
111:      function _newRestrictionManager(address[] calldata restrictionManagerWards) internal returns (address memberList) {

```
*GitHub*: [111](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L111)


### [N&#x2011;28] Use `abi.encodeCall()` instead of `abi.encodeWithSignature()`/`abi.encodeWithSelector()`
`abi.encodeCall()` has compiler [type safety](https://github.com/OpenZeppelin/openzeppelin-contracts/issues/3693), whereas the other two functions do not

*There are 4 instances of this issue:*

```solidity
File: src/token/ERC20.sol

212:             signer.staticcall(abi.encodeWithSelector(IERC1271.isValidSignature.selector, digest, signature));

```
*GitHub*: [212](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L212-L212)

```solidity
File: src/util/SafeTransferLib.sol

17:              token.call(abi.encodeWithSelector(IERC20.transferFrom.selector, from, to, value));

27:          (bool success, bytes memory data) = token.call(abi.encodeWithSelector(IERC20.transfer.selector, to, value));

37:          (bool success, bytes memory data) = token.call(abi.encodeWithSelector(IERC20.approve.selector, to, value));

```
*GitHub*: [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L17-L17), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L27-L27), [37](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L37-L37)


### [N&#x2011;29] Function state mutability can be restricted to view


*There is one instance of this issue:*

```solidity
File: src/InvestmentManager.sol

651      function _isAllowedToInvest(uint64 poolId, bytes16 trancheId, address currency, address user)
652          internal
653          returns (bool)
654:     {

```
*GitHub*: [651](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L651-L654)


### [N&#x2011;30] Memory-safe annotation preferred over comment variant
The memory-safe annotation (`assembly ("memory-safe") { ... }`), available starting in Solidity version 0.8.13 is preferred over the comment variant, which will be removed in a future breaking [release](https://docs.soliditylang.org/en/v0.8.13/assembly.html#memory-safety). The comment variant is only meant for externalized library code that needs to work in earlier versions (e.g. `SafeTransferLib` needs to be able to be used in many different versions).

*There is one instance of this issue:*

```solidity
File: src/token/Tranche.sol

106              /// @solidity memory-safe-assembly
107              assembly {
108                  sender := shr(96, calldataload(sub(calldatasize(), 20)))
109:             }

```
*GitHub*: [106](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L106-L109)


### [N&#x2011;31] Non-`external`/`public` variable names should begin with an underscore
According to the Solidity Style Guide, non-`external`/`public` variable names should begin with an [underscore](https://docs.soliditylang.org/en/latest/style-guide.html#underscore-prefix-for-non-external-functions-and-variables)

*There are 8 instances of this issue:*

```solidity
File: src/PoolManager.sol

79:      uint8 internal constant MAX_CURRENCY_DECIMALS = 18;

```
*GitHub*: [79](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L79-L79)

```solidity
File: src/Root.sol

17:      uint256 private MAX_DELAY = 4 weeks;

```
*GitHub*: [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L17-L17)

```solidity
File: src/UserEscrow.sol

17:      mapping(address => mapping(address => uint256)) destinations;

```
*GitHub*: [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L17-L17)

```solidity
File: src/gateway/routers/axelar/Router.sol

25:      string private constant axelarCentrifugeChainId = "centrifuge";

26:      string private constant axelarCentrifugeChainAddress = "0x7369626cef070000000000000000000000000000";

27:      string private constant centrifugeGatewayPrecompileAddress = "0x0000000000000000000000000000000000002048";

```
*GitHub*: [25](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L25-L25), [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L26-L26), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L27-L27)

```solidity
File: src/util/Factory.sol

27:      address immutable root;

72:      address immutable root;

```
*GitHub*: [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L27-L27), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L72-L72)


### [N&#x2011;32] Variable names for `constant`s don't follow the Solidity style guide
According to the [Style guide](https://docs.soliditylang.org/en/latest/style-guide.html#constants), for `constant` variable names, each word should use all capital letters, with underscores separating each word (CONSTANT_CASE)

*There are 4 instances of this issue:*

```solidity
File: src/gateway/routers/axelar/Router.sol

25:      string private constant axelarCentrifugeChainId = "centrifuge";

26:      string private constant axelarCentrifugeChainAddress = "0x7369626cef070000000000000000000000000000";

27:      string private constant centrifugeGatewayPrecompileAddress = "0x0000000000000000000000000000000000002048";

```
*GitHub*: [25](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L25-L25), [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L26-L26), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L27-L27)

```solidity
File: src/token/ERC20.sol

21:      string public constant version = "3";

```
*GitHub*: [21](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L21-L21)


### [N&#x2011;33] Variable names for `immutable`s should use CONSTANT_CASE
For `immutable` variable names, each word should use all capital letters, with underscores separating each word (CONSTANT_CASE)

*There are 18 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

75:      EscrowLike public immutable escrow;

76:      UserEscrowLike public immutable userEscrow;

```
*GitHub*: [75](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L75-L75), [76](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L76-L76)

```solidity
File: src/LiquidityPool.sol

55:      uint64 public immutable poolId;

56:      bytes16 public immutable trancheId;

62:      address public immutable asset;

67:      TrancheTokenLike public immutable share;

```
*GitHub*: [55](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L55-L55), [56](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L56-L56), [62](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L62-L62), [67](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L67-L67)

```solidity
File: src/PoolManager.sol

81:      EscrowLike public immutable escrow;

82:      LiquidityPoolFactoryLike public immutable liquidityPoolFactory;

83:      TrancheTokenFactoryLike public immutable trancheTokenFactory;

```
*GitHub*: [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L81-L81), [82](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L82-L82), [83](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L83-L83)

```solidity
File: src/Root.sol

19:      address public immutable escrow;

```
*GitHub*: [19](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L19-L19)

```solidity
File: src/admins/DelayedAdmin.sol

13:      Root public immutable root;

```
*GitHub*: [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L13-L13)

```solidity
File: src/admins/PauseAdmin.sol

11:      Root public immutable root;

```
*GitHub*: [11](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L11-L11)

```solidity
File: src/gateway/Gateway.sol

85:      RootLike public immutable root;

```
*GitHub*: [85](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L85-L85)

```solidity
File: src/gateway/routers/axelar/Router.sol

29:      AxelarGatewayLike public immutable axelarGateway;

```
*GitHub*: [29](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L29-L29)

```solidity
File: src/token/ERC20.sol

22:      uint8 public immutable decimals;

30:      uint256 public immutable deploymentChainId;

```
*GitHub*: [22](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L22-L22), [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L30-L30)

```solidity
File: src/util/Factory.sol

27:      address immutable root;

72:      address immutable root;

```
*GitHub*: [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L27-L27), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L72-L72)

</details>




### [N&#x2011;34] Array indicies should be referenced via `enum`s rather than via numeric literals


*There are 4 instances of this issue:*

```solidity
File: src/PoolManager.sol

286:         trancheTokenWards[0] = address(investmentManager);

287:         trancheTokenWards[1] = address(this);

290:         memberlistWards[0] = address(this);

317:         liquidityPoolWards[0] = address(investmentManager);

```
*GitHub*: [286](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L286-L286), [287](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L287-L287), [290](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L290-L290), [317](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L317-L317)


### [N&#x2011;35] Consider using named mappings
Consider moving to solidity version 0.8.18 or later, and using [named mappings](https://ethereum.stackexchange.com/a/145555) to make it easier to understand the purpose of each mapping

*There are 21 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

81:      mapping(address => mapping(address => LPValues)) public orderbook;

```
*GitHub*: [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L81-L81), [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L81-L81)

```solidity
File: src/PoolManager.sol

56:      mapping(bytes16 => Tranche) tranches;

57:      mapping(address => bool) allowedCurrencies;

72:      mapping(address => address) liquidityPools; // currency -> liquidity pool address

88:      mapping(uint64 => Pool) public pools;

91:      mapping(uint128 => address) public currencyIdToAddress;

92:      mapping(address => uint128) public currencyAddressToId;

```
*GitHub*: [56](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L56-L56), [57](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L57-L57), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L72-L72), [88](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L88-L88), [91](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L91-L91), [92](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L92-L92)

```solidity
File: src/Root.sol

21:      mapping(address => uint256) public schedule;

```
*GitHub*: [21](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L21-L21)

```solidity
File: src/UserEscrow.sol

17:      mapping(address => mapping(address => uint256)) destinations;

```
*GitHub*: [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L17-L17), [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L17-L17)

```solidity
File: src/admins/PauseAdmin.sol

13:      mapping(address => uint256) public pausers;

```
*GitHub*: [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L13-L13)

```solidity
File: src/gateway/Gateway.sol

89:      mapping(address => bool) public incomingRouters;

```
*GitHub*: [89](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L89-L89)

```solidity
File: src/token/ERC20.sol

17:      mapping(address => uint256) public wards;

25:      mapping(address => uint256) public balanceOf;

26:      mapping(address => mapping(address => uint256)) public allowance;

27:      mapping(address => uint256) public nonces;

```
*GitHub*: [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L17-L17), [25](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L25-L25), [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L26-L26), [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L26-L26), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L27-L27)

```solidity
File: src/token/RestrictionManager.sol

20:      mapping(address => uint256) public members;

```
*GitHub*: [20](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L20-L20)

```solidity
File: src/token/Tranche.sol

26:      mapping(address => bool) public liquidityPools;

```
*GitHub*: [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L26-L26)

```solidity
File: src/util/Auth.sol

8:       mapping(address => uint256) public wards;

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L8-L8)

</details>




### [N&#x2011;36] Use of `override` is unnecessary
Starting with Solidity version [0.8.8](https://docs.soliditylang.org/en/v0.8.20/contracts.html#function-overriding), using the `override` keyword when the function solely overrides an interface function, and the function doesn't exist in multiple base contracts, is unnecessary.

*There are 4 instances of this issue:*

```solidity
File: src/token/Tranche.sol

59:      function transfer(address to, uint256 value) public override restricted(_msgSender(), to, value) returns (bool) {

63       function transferFrom(address from, address to, uint256 value)
64           public
65           override
66           restricted(from, to, value)
67           returns (bool)
68:      {

72:      function mint(address to, uint256 value) public override restricted(_msgSender(), to, value) {

103:     function _msgSender() internal view virtual override returns (address sender) {

```
*GitHub*: [59](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L59-L59), [63](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L63-L68), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L72-L72), [103](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L103-L103)


### [N&#x2011;37] Consider using descriptive `constant`s when passing zero as a function argument
Passing zero as a function argument can sometimes result in a security issue (e.g. passing zero as the slippage parameter). Consider using a `constant` variable with a descriptive name, so it's clear that the argument is intentionally being used, and for the right reasons.

*There are 9 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

177:         require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

190:         require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

202:         require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

213:         require(liquidityPool.checkTransferRestriction(address(0), user, 0), "InvestmentManager/not-a-member");

308:             LiquidityPoolLike(liquidityPool).checkTransferRestriction(address(0), user, 0),

473:         require(lPool.checkTransferRestriction(msg.sender, user, 0), "InvestmentManager/trancheTokens-not-a-member");

658:             LiquidityPoolLike(liquidityPool).checkTransferRestriction(address(0), user, 0),

```
*GitHub*: [177](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L177-L177), [190](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L190-L190), [202](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L202-L202), [213](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L213-L213), [308](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L308-L308), [473](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L473-L473), [658](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L658-L658)

```solidity
File: src/gateway/Messages.sol

69:          _call = Call(BytesLib.toUint8(_msg, 0));

841:         return bytes9(BytesLib.slice(abi.encodePacked(uint8(domain), chainId), 0, 9));

```
*GitHub*: [69](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L69-L69), [841](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L841-L841)


### [N&#x2011;38] Variables need not be initialized to false
The default value for boolean variables is `false`, so initializing them to `false` is superfluous.

*There is one instance of this issue:*

```solidity
File: src/Root.sol

23:      bool public paused = false;

```
*GitHub*: [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L23-L23)


### [N&#x2011;39] Variables need not be initialized to zero
The default value for variables is zero, so initializing them to zero is superfluous.

*There are 9 instances of this issue:*

```solidity
File: src/gateway/Messages.sol

848:         for (uint256 i = 0; i < 128; i++) {

862:         uint8 i = 0;

869:         for (uint8 j = 0; j < i; j++) {

888:         uint8 i = 0;

```
*GitHub*: [848](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L848-L848), [862](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L862-L862), [869](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L869-L869), [888](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L888-L888)

```solidity
File: src/token/RestrictionManager.sol

15:      uint8 public constant SUCCESS_CODE = 0;

64:          for (uint256 i = 0; i < userLength; i++) {

```
*GitHub*: [15](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L15-L15), [64](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L64-L64)

```solidity
File: src/util/Factory.sol

47:          for (uint256 i = 0; i < wards.length; i++) {

103:         for (uint256 i = 0; i < trancheTokenWards.length; i++) {

117:         for (uint256 i = 0; i < restrictionManagerWards.length; i++) {

```
*GitHub*: [47](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L47-L47), [103](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L103-L103), [117](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L117-L117)


### [N&#x2011;40] Consider using `safePermit()`
The [Anyswap hack](https://media.dedaub.com/phantom-functions-and-the-billion-dollar-no-op-c56f062ae49f#ef54) occurred because the `permit()` function didn't really exist, but the fallback function that took its place did not complain. Consider using [`safePermit()`](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/5229b75785213541e93fb0a466a3d102a3bf5dbe/contracts/token/ERC20/utils/SafeERC20.sol#L89-L105) which ensures that the permit actually went through.

*There is one instance of this issue:*

```solidity
File: src/LiquidityPool.sol

223:         ERC20PermitLike(asset).permit(owner, address(investmentManager), assets, deadline, v, r, s);

```
*GitHub*: [223](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L223-L223)


### [N&#x2011;41] Function state mutability can be restricted to pure


*There are 3 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

676      function _toPriceDecimals(uint128 _value, uint8 decimals, address liquidityPool)
677          internal
678          view
679          returns (uint256 value)
680:     {

686      function _fromPriceDecimals(uint256 _value, uint8 decimals, address liquidityPool)
687          internal
688          view
689          returns (uint128 value)
690:     {

```
*GitHub*: [676](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L676-L680), [686](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L686-L690)

```solidity
File: src/token/RestrictionManager.sol

36:      function messageForTransferRestriction(uint8 restrictionCode) public view returns (string memory) {

```
*GitHub*: [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L36-L36)


### [N&#x2011;42] Unused local variable


*There is one instance of this issue:*

```solidity
File: src/gateway/Gateway.sol

/// @audit _price
302:                 uint128 _price

```
*GitHub*: [302](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L302-L302)


### [N&#x2011;43] `constant`s should be defined rather than using magic numbers
Even [assembly](https://github.com/code-423n4/2022-05-opensea-seaport/blob/9d7ce4d08bf3c3010304a0476a785c70c0e90ae7/contracts/lib/TokenTransferrer.sol#L35-L39) can benefit from using readable constants instead of hex/numeric literals

*There are 75 instances of this issue:*

```solidity
File: src/Root.sol

17:      uint256 private MAX_DELAY = 4 weeks;

```
*GitHub*: [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L17-L17)

```solidity
File: src/gateway/Messages.sol

89:          currencyAddress = BytesLib.toAddress(_msg, 17);

127:         currency = BytesLib.toUint128(_msg, 9);

180:         trancheId = BytesLib.toBytes16(_msg, 9);

181:         tokenName = _bytes128ToString(BytesLib.slice(_msg, 25, 128));

182:         tokenSymbol = _bytes32ToString(BytesLib.toBytes32(_msg, 153));

183:         decimals = BytesLib.toUint8(_msg, 185);

184:         price = BytesLib.toUint128(_msg, 186);

223:         trancheId = BytesLib.toBytes16(_msg, 9);

224:         user = BytesLib.toAddress(_msg, 25);

225:         validUntil = BytesLib.toUint64(_msg, 57);

255:         trancheId = BytesLib.toBytes16(_msg, 9);

256:         currencyId = BytesLib.toUint128(_msg, 25);

257:         price = BytesLib.toUint128(_msg, 41);

287:         sender = BytesLib.toBytes32(_msg, 17);

288:         receiver = BytesLib.toBytes32(_msg, 49);

289:         amount = BytesLib.toUint128(_msg, 81);

300:         recipient = BytesLib.toAddress(_msg, 49);

301:         amount = BytesLib.toUint128(_msg, 81);

357:         trancheId = BytesLib.toBytes16(_msg, 9);

360:         destinationAddress = BytesLib.toAddress(_msg, 66);

361:         amount = BytesLib.toUint128(_msg, 98);

394:         trancheId = BytesLib.toBytes16(_msg, 9);

395:         investor = BytesLib.toBytes32(_msg, 25);

396:         currency = BytesLib.toUint128(_msg, 57);

397:         amount = BytesLib.toUint128(_msg, 73);

522:         trancheId = BytesLib.toBytes16(_msg, 9);

523:         investor = BytesLib.toBytes32(_msg, 25);

524:         currency = BytesLib.toUint128(_msg, 57);

553:         trancheId = BytesLib.toBytes16(_msg, 9);

554:         investor = BytesLib.toBytes32(_msg, 25);

555:         currency = BytesLib.toUint128(_msg, 57);

580:         trancheId = BytesLib.toBytes16(_msg, 9);

581:         investor = BytesLib.toAddress(_msg, 25);

582:         currency = BytesLib.toUint128(_msg, 57);

583:         trancheTokenPayout = BytesLib.toUint128(_msg, 73);

608:         trancheId = BytesLib.toBytes16(_msg, 9);

609:         investor = BytesLib.toAddress(_msg, 25);

610:         currency = BytesLib.toUint128(_msg, 57);

611:         trancheTokensPayout = BytesLib.toUint128(_msg, 73);

650:         trancheId = BytesLib.toBytes16(_msg, 9);

651:         investor = BytesLib.toAddress(_msg, 25);

652:         currency = BytesLib.toUint128(_msg, 57);

653:         currencyPayout = BytesLib.toUint128(_msg, 73);

654:         trancheTokensPayout = BytesLib.toUint128(_msg, 89);

693:         trancheId = BytesLib.toBytes16(_msg, 9);

694:         investor = BytesLib.toAddress(_msg, 25);

695:         currency = BytesLib.toUint128(_msg, 57);

696:         currencyPayout = BytesLib.toUint128(_msg, 73);

697:         trancheTokensPayout = BytesLib.toUint128(_msg, 89);

761:         trancheId = BytesLib.toBytes16(_msg, 9);

762:         tokenName = _bytes128ToString(BytesLib.slice(_msg, 25, 128));

763:         tokenSymbol = _bytes32ToString(BytesLib.toBytes32(_msg, 153));

780:         trancheId = BytesLib.toBytes16(_msg, 9);

781:         investor = BytesLib.toAddress(_msg, 25);

782:         currency = BytesLib.toUint128(_msg, 57);

799:         trancheId = BytesLib.toBytes16(_msg, 9);

800:         investor = BytesLib.toAddress(_msg, 25);

801:         currency = BytesLib.toUint128(_msg, 57);

830:         trancheId = BytesLib.toBytes16(_msg, 9);

831:         investmentLimit = BytesLib.toUint128(_msg, 25);

841:         return bytes9(BytesLib.slice(abi.encodePacked(uint8(domain), chainId), 0, 9));

846:         bytes memory result = new bytes(128);

852:                 result[i] = 0x00;

848:         for (uint256 i = 0; i < 128; i++) {

860:         require(_bytes128.length == 128, "Input should be 128 bytes");

863:         while (i < 128 && _bytes128[i] != 0) {

879:             return 0x0;

889:         while (i < 32 && _bytes32[i] != 0) {

893:         for (i = 0; i < 32 && _bytes32[i] != 0; i++) {

```
*GitHub*: [89](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L89-L89), [127](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L127-L127), [180](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L180-L180), [181](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L181-L181), [181](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L181-L181), [182](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L182-L182), [183](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L183-L183), [184](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L184-L184), [223](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L223-L223), [224](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L224-L224), [225](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L225-L225), [255](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L255-L255), [256](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L256-L256), [257](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L257-L257), [287](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L287-L287), [288](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L288-L288), [289](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L289-L289), [300](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L300-L300), [301](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L301-L301), [357](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L357-L357), [360](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L360-L360), [361](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L361-L361), [394](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L394-L394), [395](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L395-L395), [396](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L396-L396), [397](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L397-L397), [522](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L522-L522), [523](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L523-L523), [524](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L524-L524), [553](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L553-L553), [554](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L554-L554), [555](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L555-L555), [580](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L580-L580), [581](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L581-L581), [582](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L582-L582), [583](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L583-L583), [608](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L608-L608), [609](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L609-L609), [610](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L610-L610), [611](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L611-L611), [650](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L650-L650), [651](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L651-L651), [652](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L652-L652), [653](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L653-L653), [654](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L654-L654), [693](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L693-L693), [694](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L694-L694), [695](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L695-L695), [696](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L696-L696), [697](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L697-L697), [761](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L761-L761), [762](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L762-L762), [762](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L762-L762), [763](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L763-L763), [780](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L780-L780), [781](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L781-L781), [782](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L782-L782), [799](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L799-L799), [800](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L800-L800), [801](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L801-L801), [830](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L830-L830), [831](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L831-L831), [841](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L841-L841), [846](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L846-L846), [852](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L852-L852), [848](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L848-L848), [860](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L860-L860), [863](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L863-L863), [879](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L879-L879), [889](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L889-L889), [893](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L893-L893)

```solidity
File: src/token/ERC20.sol

197:         if (signature.length == 65) {

213:         return (success && result.length == 32 && abi.decode(result, (bytes4)) == IERC1271.isValidSignature.selector);

```
*GitHub*: [197](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L197-L197), [213](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L213-L213)

```solidity
File: src/token/Tranche.sol

104:         if (isTrustedForwarder(msg.sender) && msg.data.length >= 20) {

```
*GitHub*: [104](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L104-L104)


### [N&#x2011;44] Consider implementing EIP-5267 to securely describe EIP-712 domains being used
[EIP-5267](https://eips.ethereum.org/EIPS/eip-5267) is a standard which allows for the retrieval and description of EIP-712 hash domains. This allows external tools to allow users to not just view the struct fields being signed, but the fields the domain the signature contains as well. This is especially useful when a project may exist on multiple chains and or in multiple contracts, and allows users/tools to verify that the signature is for the right fork, chain, version, contract, etc.

*There is one instance of this issue:*

```solidity
File: src/token/ERC20.sol

70:                  keccak256("EIP712Domain(string name,string version,uint256 chainId,address verifyingContract)"),

```
*GitHub*: [70](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L70-L70)


### [N&#x2011;45] Events are missing sender information
When an action is triggered based on a user's action, not being able to filter based on who triggered the action makes event processing a lot more cumbersome. Including the `msg.sender` the events of these types of action will make events much more useful to end users, especially when `msg.sender` is not `tx.origin`.

*There are 45 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

107:         emit File(what, data);

479:         emit DepositProcessed(liquidityPool, user, currencyAmount);

547:         emit RedemptionProcessed(liquidityPool, user, trancheTokenAmount);

```
*GitHub*: [107](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L107-L107), [479](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L479-L479), [547](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L547-L547)

```solidity
File: src/LiquidityPool.sol

106:         emit File(what, data);

143:         emit Deposit(address(this), receiver, assets, shares);

151:         emit Deposit(address(this), receiver, assets, shares);

182:         emit Withdraw(address(this), receiver, owner, assets, sharesRedeemed);

206:         emit Withdraw(address(this), receiver, owner, currencyPayout, shares);

216:         emit DepositRequested(owner, assets);

225:         emit DepositRequested(owner, assets);

233:         emit RedeemRequested(owner, shares);

242:         emit RedeemRequested(owner, shares);

261:         emit DepositCollected(receiver);

267:         emit RedeemCollected(receiver);

327:         emit UpdatePrice(price);

```
*GitHub*: [106](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L106-L106), [143](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L143-L143), [151](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L151-L151), [182](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L182-L182), [206](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L206-L206), [216](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L216-L216), [225](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L225-L225), [233](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L233-L233), [242](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L242-L242), [261](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L261-L261), [267](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L267-L267), [327](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L327-L327)

```solidity
File: src/PoolManager.sol

124:         emit File(what, data);

173:         emit PoolAdded(poolId);

187:         emit PoolCurrencyAllowed(currency, poolId);

211:         emit TrancheAdded(poolId, trancheId);

254:         emit CurrencyAdded(currency, currencyAddress);

303:         emit TrancheTokenDeployed(poolId, trancheId);

331:         emit LiquidityPoolDeployed(poolId, trancheId, liquidityPool);

```
*GitHub*: [124](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L124-L124), [173](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L173-L173), [187](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L187-L187), [211](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L211-L211), [254](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L254-L254), [303](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L303-L303), [331](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L331-L331)

```solidity
File: src/Root.sol

50:          emit File(what, data);

56:          emit Pause();

61:          emit Unpause();

67:          emit RelyScheduled(target, schedule[target]);

72:          emit RelyCancelled(target);

80:          emit Rely(target);

92:          emit RelyContract(target, user);

100:         emit DenyContract(target, user);

```
*GitHub*: [50](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L50-L50), [56](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L56-L56), [61](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L61-L61), [67](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L67-L67), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L72-L72), [80](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L80-L80), [92](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L92-L92), [100](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L100-L100)

```solidity
File: src/admins/PauseAdmin.sol

36:          emit AddPauser(user);

41:          emit RemovePauser(user);

```
*GitHub*: [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L36-L36), [41](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L41-L41)

```solidity
File: src/gateway/Gateway.sol

134:         emit File(what, data);

139:         emit AddIncomingRouter(router);

144:         emit RemoveIncomingRouter(router);

149:         emit UpdateOutgoingRouter(router);

```
*GitHub*: [134](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L134-L134), [139](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L139-L139), [144](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L144-L144), [149](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L149-L149)

```solidity
File: src/gateway/routers/axelar/Router.sol

69:          emit File(what, data);

```
*GitHub*: [69](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L69-L69)

```solidity
File: src/token/ERC20.sol

59:          emit Rely(user);

64:          emit Deny(user);

87:          emit File(what, data);

```
*GitHub*: [59](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L59-L59), [64](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L64-L64), [87](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L87-L87)

```solidity
File: src/token/Tranche.sol

45:          emit File(what, data);

50:          emit AddLiquidityPool(liquidityPool);

55:          emit RemoveLiquidityPool(liquidityPool);

```
*GitHub*: [45](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L45-L45), [50](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L50-L50), [55](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L55-L55)

```solidity
File: src/util/Auth.sol

16:          emit Rely(user);

22:          emit Deny(user);

```
*GitHub*: [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L16-L16), [22](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L22-L22)

</details>




### [N&#x2011;46] Consider adding a block/deny-list
Doing so will significantly increase centralization, but will help to prevent hackers from using stolen tokens

*There are 6 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

69:  contract InvestmentManager is Auth {

```
*GitHub*: [69](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L69-L69)

```solidity
File: src/LiquidityPool.sol

52:  contract LiquidityPool is Auth, IERC4626 {

```
*GitHub*: [52](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L52-L52)

```solidity
File: src/PoolManager.sol

78:  contract PoolManager is Auth {

```
*GitHub*: [78](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L78-L78)

```solidity
File: src/UserEscrow.sol

15   contract UserEscrow is Auth {
16:      /// @dev Map by token and destination

```
*GitHub*: [15](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L15-L16)

```solidity
File: src/token/ERC20.sol

16:  contract ERC20 is Context {

```
*GitHub*: [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L16-L16)

```solidity
File: src/token/Tranche.sol

23:  contract TrancheToken is ERC20, ERC1404Like {

```
*GitHub*: [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L23-L23)


### [N&#x2011;47] Unused function parameter
Comment out the variable name to suppress compiler warnings

*There are 4 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

/// @audit liquidityPool
676:     function _toPriceDecimals(uint128 _value, uint8 decimals, address liquidityPool)

/// @audit liquidityPool
686:     function _fromPriceDecimals(uint256 _value, uint8 decimals, address liquidityPool)

```
*GitHub*: [676](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L676-L676), [686](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L686-L686)

```solidity
File: src/token/RestrictionManager.sol

/// @audit from
/// @audit value
28:      function detectTransferRestriction(address from, address to, uint256 value) public view returns (uint8) {

```
*GitHub*: [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L28-L28), [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L28-L28)


### [N&#x2011;48] Unused `event` definition
Note that there may be cases where an event superficially appears to be used, but this is only because there are multiple definitions of the event in different files. In such cases, the event definition should be moved into a separate file. The instances below are the unused definitions.

*There are 3 instances of this issue:*

```solidity
File: src/PoolManager.sol

99:      event TrancheDeployed(uint64 indexed poolId, bytes16 indexed trancheId, address indexed token);

```
*GitHub*: [99](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L99-L99)

```solidity
File: src/admins/DelayedAdmin.sol

16:      event File(bytes32 indexed what, address indexed data);

```
*GitHub*: [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L16-L16)

```solidity
File: src/admins/PauseAdmin.sol

19:      event File(bytes32 indexed what, address indexed data);

```
*GitHub*: [19](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L19-L19)


### [N&#x2011;49] Contract declarations should have NatSpec descriptions
e.g. `@dev` or `@notice`, and it must appear above the contract definition braces in order to be identified by the compiler as NatSpec

*There are 32 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/Escrow.sol

7:   interface ApproveLike {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L7-L7)

```solidity
File: src/InvestmentManager.sol

8:   interface GatewayLike {

23:  interface ERC20Like {

31:  interface LiquidityPoolLike is ERC20Like {

41:  interface PoolManagerLike {

49:  interface EscrowLike {

53:  interface UserEscrowLike {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L8-L8), [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L23-L23), [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L31-L31), [41](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L41-L41), [49](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L49-L49), [53](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L53-L53)

```solidity
File: src/LiquidityPool.sol

9:   interface ERC20PermitLike {

16:  interface TrancheTokenLike is IERC20, ERC20PermitLike {

20:  interface InvestmentManagerLike {

```
*GitHub*: [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L9-L9), [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L16-L16), [20](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L20-L20)

```solidity
File: src/PoolManager.sol

11:  interface GatewayLike {

30:  interface LiquidityPoolLike {

34:  interface InvestmentManagerLike {

40:  interface EscrowLike {

44:  interface ERC2771Like {

48:  interface AuthLike {

```
*GitHub*: [11](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L11-L11), [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L30-L30), [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L34-L34), [40](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L40-L40), [44](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L44-L44), [48](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L48-L48)

```solidity
File: src/Root.sol

6:   interface AuthLike {

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L6-L6)

```solidity
File: src/UserEscrow.sol

7:   interface ERC20Like {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L7-L7)

```solidity
File: src/gateway/Gateway.sol

7:   interface InvestmentManagerLike {

41:  interface PoolManagerLike {

64:  interface RouterLike {

68:  interface AuthLike {

72:  interface RootLike {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L7-L7), [41](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L41-L41), [64](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L64-L64), [68](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L68-L68), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L72-L72)

```solidity
File: src/gateway/routers/axelar/Router.sol

6:   interface AxelarGatewayLike {

18:  interface GatewayLike {

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L6-L6), [18](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L18-L18)

```solidity
File: src/token/ERC20.sol

8:   interface IERC1271 {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L8-L8)

```solidity
File: src/token/RestrictionManager.sol

6:   interface MemberlistLike {

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L6-L6)

```solidity
File: src/token/Tranche.sol

7:   interface TrancheTokenLike is IERC20 {

12:  interface ERC1404Like {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L7-L7), [12](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L12-L12)

```solidity
File: src/util/Factory.sol

9:   interface RootLike {

13:  interface LiquidityPoolFactoryLike {

55:  interface TrancheTokenFactoryLike {

```
*GitHub*: [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L9-L9), [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L13-L13), [55](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L55-L55)

</details>




### [N&#x2011;50] Modifier declarations should have NatSpec descriptions


*There are 9 instances of this issue:*

```solidity
File: src/admins/PauseAdmin.sol

28       modifier canPause() {
29           require(pausers[msg.sender] == 1, "PauseAdmin/not-authorized-to-pause");
30           _;
31:      }

```
*GitHub*: [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L28-L31)

```solidity
File: src/gateway/Gateway.sol

109      modifier onlyInvestmentManager() {
110          require(msg.sender == address(investmentManager), "Gateway/only-investment-manager-allowed-to-call");
111          _;
112:     }

114      modifier onlyPoolManager() {
115          require(msg.sender == address(poolManager), "Gateway/only-pool-manager-allowed-to-call");
116          _;
117:     }

119      modifier onlyIncomingRouter() {
120          require(incomingRouters[msg.sender], "Gateway/only-router-allowed-to-call");
121          _;
122:     }

124      modifier pauseable() {
125          require(!root.paused(), "Gateway/paused");
126          _;
127:     }

```
*GitHub*: [109](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L109-L112), [114](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L114-L117), [119](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L119-L122), [124](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L124-L127)

```solidity
File: src/gateway/routers/axelar/Router.sol

43       modifier onlyCentrifugeChainOrigin(string calldata sourceChain, string calldata sourceAddress) {
44           require(msg.sender == address(axelarGateway), "AxelarRouter/invalid-origin");
45           require(
46               keccak256(bytes(axelarCentrifugeChainId)) == keccak256(bytes(sourceChain)),
47               "AxelarRouter/invalid-source-chain"
48           );
49           require(
50               keccak256(bytes(axelarCentrifugeChainAddress)) == keccak256(bytes(sourceAddress)),
51               "AxelarRouter/invalid-source-address"
52           );
53           _;
54:      }

56       modifier onlyGateway() {
57           require(msg.sender == address(gateway), "AxelarRouter/only-gateway-allowed-to-call");
58           _;
59:      }

```
*GitHub*: [43](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L43-L54), [56](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L56-L59)

```solidity
File: src/token/ERC20.sol

51       modifier auth() {
52           // Custom auth modifier that uses _msgSender()
53           require(wards[_msgSender()] == 1, "Auth/not-authorized");
54           _;
55:      }

```
*GitHub*: [51](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L51-L55)

```solidity
File: src/token/Tranche.sol

35       modifier restricted(address from, address to, uint256 value) {
36           uint8 restrictionCode = detectTransferRestriction(from, to, value);
37           require(restrictionCode == restrictionManager.SUCCESS_CODE(), messageForTransferRestriction(restrictionCode));
38           _;
39:      }

```
*GitHub*: [35](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L35-L39)


### [N&#x2011;51] Event declarations should have NatSpec descriptions


*There are 46 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/Escrow.sol

15:      event Approve(address indexed token, address indexed spender, uint256 value);

```
*GitHub*: [15](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L15-L15)

```solidity
File: src/InvestmentManager.sol

84:      event File(bytes32 indexed what, address data);

85:      event DepositProcessed(address indexed liquidityPool, address indexed user, uint128 indexed currencyAmount);

86:      event RedemptionProcessed(address indexed liquidityPool, address indexed user, uint128 indexed trancheTokenAmount);

```
*GitHub*: [84](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L84-L84), [85](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L85-L85), [86](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L86-L86)

```solidity
File: src/LiquidityPool.sol

78:      event File(bytes32 indexed what, address data);

79:      event DepositRequested(address indexed owner, uint256 assets);

80:      event RedeemRequested(address indexed owner, uint256 shares);

81:      event DepositCollected(address indexed owner);

82:      event RedeemCollected(address indexed owner);

83:      event UpdatePrice(uint128 price);

```
*GitHub*: [78](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L78-L78), [79](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L79-L79), [80](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L80-L80), [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L81-L81), [82](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L82-L82), [83](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L83-L83)

```solidity
File: src/PoolManager.sol

95:      event File(bytes32 indexed what, address data);

96:      event PoolAdded(uint64 indexed poolId);

97:      event PoolCurrencyAllowed(uint128 indexed currency, uint64 indexed poolId);

98:      event TrancheAdded(uint64 indexed poolId, bytes16 indexed trancheId);

99:      event TrancheDeployed(uint64 indexed poolId, bytes16 indexed trancheId, address indexed token);

100:     event CurrencyAdded(uint128 indexed currency, address indexed currencyAddress);

101:     event LiquidityPoolDeployed(uint64 indexed poolId, bytes16 indexed trancheId, address indexed liquidityPoool);

102:     event TrancheTokenDeployed(uint64 indexed poolId, bytes16 indexed trancheId);

```
*GitHub*: [95](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L95-L95), [96](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L96-L96), [97](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L97-L97), [98](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L98-L98), [99](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L99-L99), [100](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L100-L100), [101](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L101-L101), [102](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L102-L102)

```solidity
File: src/Root.sol

26:      event File(bytes32 indexed what, uint256 data);

27:      event Pause();

28:      event Unpause();

29:      event RelyScheduled(address indexed target, uint256 indexed scheduledTime);

30:      event RelyCancelled(address indexed target);

31:      event RelyContract(address target, address indexed user);

32:      event DenyContract(address target, address indexed user);

```
*GitHub*: [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L26-L26), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L27-L27), [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L28-L28), [29](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L29-L29), [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L30-L30), [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L31-L31), [32](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L32-L32)

```solidity
File: src/UserEscrow.sol

20:      event TransferIn(address indexed token, address indexed source, address indexed destination, uint256 amount);

21:      event TransferOut(address indexed token, address indexed destination, uint256 amount);

```
*GitHub*: [20](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L20-L20), [21](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L21-L21)

```solidity
File: src/admins/DelayedAdmin.sol

16:      event File(bytes32 indexed what, address indexed data);

```
*GitHub*: [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L16-L16)

```solidity
File: src/admins/PauseAdmin.sol

15:      event AddPauser(address indexed user);

16:      event RemovePauser(address indexed user);

19:      event File(bytes32 indexed what, address indexed data);

```
*GitHub*: [15](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L15-L15), [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L16-L16), [19](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L19-L19)

```solidity
File: src/gateway/Gateway.sol

93:      event AddIncomingRouter(address indexed router);

94:      event RemoveIncomingRouter(address indexed router);

95:      event UpdateOutgoingRouter(address indexed router);

96:      event File(bytes32 indexed what, address data);

```
*GitHub*: [93](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L93-L93), [94](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L94-L94), [95](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L95-L95), [96](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L96-L96)

```solidity
File: src/gateway/routers/axelar/Router.sol

34:      event File(bytes32 indexed what, address addr);

```
*GitHub*: [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L34-L34)

```solidity
File: src/token/ERC20.sol

36:      event Rely(address indexed user);

37:      event Deny(address indexed user);

38:      event File(bytes32 indexed what, string data);

39:      event Approval(address indexed owner, address indexed spender, uint256 value);

40:      event Transfer(address indexed from, address indexed to, uint256 value);

```
*GitHub*: [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L36-L36), [37](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L37-L37), [38](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L38-L38), [39](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L39-L39), [40](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L40-L40)

```solidity
File: src/token/Tranche.sol

29:      event File(bytes32 indexed what, address data);

30:      event AddLiquidityPool(address indexed liquidityPool);

31:      event RemoveLiquidityPool(address indexed liquidityPool);

```
*GitHub*: [29](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L29-L29), [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L30-L30), [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L31-L31)

```solidity
File: src/util/Auth.sol

10:      event Rely(address indexed user);

11:      event Deny(address indexed user);

```
*GitHub*: [10](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L10-L10), [11](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L11-L11)

</details>




### [N&#x2011;52] State variable declarations should have NatSpec descriptions
e.g. `@notice` for public state variables, and `@dev` for [non-public](https://docs.soliditylang.org/en/latest/natspec-format.html#tags) ones

*There are 55 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

75:      EscrowLike public immutable escrow;

76:      UserEscrowLike public immutable userEscrow;

78:      GatewayLike public gateway;

79:      PoolManagerLike public poolManager;

81:      mapping(address => mapping(address => LPValues)) public orderbook;

```
*GitHub*: [75](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L75-L75), [76](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L76-L76), [78](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L78-L78), [79](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L79-L79), [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L81-L81)

```solidity
File: src/LiquidityPool.sol

55:      uint64 public immutable poolId;

56:      bytes16 public immutable trancheId;

69:      InvestmentManagerLike public investmentManager;

```
*GitHub*: [55](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L55-L55), [56](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L56-L56), [69](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L69-L69)

```solidity
File: src/PoolManager.sol

79:      uint8 internal constant MAX_CURRENCY_DECIMALS = 18;

81:      EscrowLike public immutable escrow;

82:      LiquidityPoolFactoryLike public immutable liquidityPoolFactory;

83:      TrancheTokenFactoryLike public immutable trancheTokenFactory;

85:      GatewayLike public gateway;

86:      InvestmentManagerLike public investmentManager;

88:      mapping(uint64 => Pool) public pools;

92:      mapping(address => uint128) public currencyAddressToId;

```
*GitHub*: [79](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L79-L79), [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L81-L81), [82](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L82-L82), [83](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L83-L83), [85](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L85-L85), [86](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L86-L86), [88](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L88-L88), [92](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L92-L92)

```solidity
File: src/Root.sol

19:      address public immutable escrow;

21:      mapping(address => uint256) public schedule;

22:      uint256 public delay;

23:      bool public paused = false;

```
*GitHub*: [19](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L19-L19), [21](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L21-L21), [22](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L22-L22), [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L23-L23)

```solidity
File: src/admins/DelayedAdmin.sol

13:      Root public immutable root;

```
*GitHub*: [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L13-L13)

```solidity
File: src/admins/PauseAdmin.sol

11:      Root public immutable root;

13:      mapping(address => uint256) public pausers;

```
*GitHub*: [11](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L11-L11), [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L13-L13)

```solidity
File: src/gateway/Gateway.sol

85:      RootLike public immutable root;

86:      InvestmentManagerLike public investmentManager;

87:      PoolManagerLike public poolManager;

89:      mapping(address => bool) public incomingRouters;

90:      RouterLike public outgoingRouter;

```
*GitHub*: [85](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L85-L85), [86](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L86-L86), [87](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L87-L87), [89](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L89-L89), [90](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L90-L90)

```solidity
File: src/gateway/routers/axelar/Router.sol

25:      string private constant axelarCentrifugeChainId = "centrifuge";

26:      string private constant axelarCentrifugeChainAddress = "0x7369626cef070000000000000000000000000000";

27:      string private constant centrifugeGatewayPrecompileAddress = "0x0000000000000000000000000000000000002048";

29:      AxelarGatewayLike public immutable axelarGateway;

31:      GatewayLike public gateway;

```
*GitHub*: [25](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L25-L25), [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L26-L26), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L27-L27), [29](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L29-L29), [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L31-L31)

```solidity
File: src/token/ERC20.sol

17:      mapping(address => uint256) public wards;

19:      string public name;

20:      string public symbol;

21:      string public constant version = "3";

22:      uint8 public immutable decimals;

23:      uint256 public totalSupply;

25:      mapping(address => uint256) public balanceOf;

26:      mapping(address => mapping(address => uint256)) public allowance;

27:      mapping(address => uint256) public nonces;

30:      uint256 public immutable deploymentChainId;

31:      bytes32 private immutable _DOMAIN_SEPARATOR;

32       bytes32 public constant PERMIT_TYPEHASH =
33:          keccak256("Permit(address owner,address spender,uint256 value,uint256 nonce,uint256 deadline)");

```
*GitHub*: [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L17-L17), [19](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L19-L19), [20](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L20-L20), [21](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L21-L21), [22](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L22-L22), [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L23-L23), [25](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L25-L25), [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L26-L26), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L27-L27), [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L30-L30), [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L31-L31), [32](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L32-L33)

```solidity
File: src/token/RestrictionManager.sol

15:      uint8 public constant SUCCESS_CODE = 0;

16:      uint8 public constant DESTINATION_NOT_A_MEMBER_RESTRICTION_CODE = 1;

17:      string public constant SUCCESS_MESSAGE = "RestrictionManager/transfer-allowed";

18:      string public constant DESTINATION_NOT_A_MEMBER_RESTRICTION_MESSAGE = "RestrictionManager/destination-not-a-member";

20:      mapping(address => uint256) public members;

```
*GitHub*: [15](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L15-L15), [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L16-L16), [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L17-L17), [18](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L18-L18), [20](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L20-L20)

```solidity
File: src/token/Tranche.sol

24:      ERC1404Like public restrictionManager;

26:      mapping(address => bool) public liquidityPools;

```
*GitHub*: [24](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L24-L24), [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L26-L26)

```solidity
File: src/util/Auth.sol

8:       mapping(address => uint256) public wards;

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L8-L8)

```solidity
File: src/util/Factory.sol

27:      address immutable root;

72:      address immutable root;

```
*GitHub*: [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L27-L27), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L72-L72)

</details>




### [N&#x2011;53] Function declarations should have NatSpec descriptions


*There are 223 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/Escrow.sol

8:       function approve(address, uint256) external returns (bool);

17:      constructor() {

23:      function approve(address token, address spender, uint256 value) external auth {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L8-L8), [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L17-L17), [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L23-L23)

```solidity
File: src/InvestmentManager.sol

9        function increaseInvestOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency, uint128 amount)
10:          external;

11       function decreaseInvestOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency, uint128 amount)
12:          external;

13       function increaseRedeemOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency, uint128 amount)
14:          external;

15       function decreaseRedeemOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency, uint128 amount)
16:          external;

17:      function collectInvest(uint64 poolId, bytes16 trancheId, address investor, uint128 currency) external;

18:      function collectRedeem(uint64 poolId, bytes16 trancheId, address investor, uint128 currency) external;

19:      function cancelInvestOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency) external;

20:      function cancelRedeemOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency) external;

24:      function approve(address token, address spender, uint256 value) external;

25:      function transferFrom(address from, address to, uint256 amount) external returns (bool);

26:      function decimals() external view returns (uint8);

27:      function mint(address, uint256) external;

28:      function burn(address, uint256) external;

32:      function poolId() external returns (uint64);

33:      function trancheId() external returns (bytes16);

34:      function asset() external view returns (address);

35:      function hasMember(address) external returns (bool);

36:      function updatePrice(uint128 price) external;

37:      function checkTransferRestriction(address from, address to, uint256 value) external view returns (bool);

38:      function latestPrice() external view returns (uint128);

42:      function currencyIdToAddress(uint128 currencyId) external view returns (address);

43:      function currencyAddressToId(address addr) external view returns (uint128);

44:      function getTrancheToken(uint64 poolId, bytes16 trancheId) external view returns (address);

45:      function getLiquidityPool(uint64 poolId, bytes16 trancheId, address currency) external view returns (address);

46:      function isAllowedAsPoolCurrency(uint64 poolId, address currencyAddress) external view returns (bool);

50:      function approve(address token, address spender, uint256 value) external;

54:      function transferIn(address token, address source, address destination, uint256 amount) external;

55:      function transferOut(address token, address owner, address destination, uint256 amount) external;

88:      constructor(address escrow_, address userEscrow_) {

103:     function file(bytes32 what, address data) external auth {

174:     function decreaseDepositRequest(uint256 _currencyAmount, address user) public auth {

187:     function decreaseRedeemRequest(uint256 _trancheTokenAmount, address user) public auth {

200:     function collectDeposit(address user) public auth {

211:     function collectRedeem(address user) public auth {

223      function updateTrancheTokenPrice(uint64 poolId, bytes16 trancheId, uint128 currencyId, uint128 price)
224          public
225          onlyGateway
226:     {

234      function handleExecutedCollectInvest(
235          uint64 poolId,
236          bytes16 trancheId,
237          address recipient,
238          uint128 currency,
239          uint128 currencyPayout,
240          uint128 trancheTokensPayout
241:     ) public onlyGateway {

255      function handleExecutedCollectRedeem(
256          uint64 poolId,
257          bytes16 trancheId,
258          address recipient,
259          uint128 currency,
260          uint128 currencyPayout,
261          uint128 trancheTokensPayout
262:     ) public onlyGateway {

277      function handleExecutedDecreaseInvestOrder(
278          uint64 poolId,
279          bytes16 trancheId,
280          address user,
281          uint128 currency,
282          uint128 currencyPayout
283:     ) public onlyGateway {

294      function handleExecutedDecreaseRedeemOrder(
295          uint64 poolId,
296          bytes16 trancheId,
297          address user,
298          uint128 currency,
299          uint128 trancheTokenPayout
300:     ) public onlyGateway {

319:     function totalAssets(uint256 totalSupply, address liquidityPool) public view returns (uint256 _totalAssets) {

551:     function calculateDepositPrice(address user, address liquidityPool) public view returns (uint256 depositPrice) {

560:     function calculateRedeemPrice(address user, address liquidityPool) public view returns (uint256 redeemPrice) {

569      function _calculatePrice(uint128 currencyAmount, uint128 trancheTokenAmount, address liquidityPool)
570          public
571          view
572          returns (uint256 depositPrice)
573:     {

```
*GitHub*: [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L9-L10), [11](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L11-L12), [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L13-L14), [15](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L15-L16), [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L17-L17), [18](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L18-L18), [19](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L19-L19), [20](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L20-L20), [24](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L24-L24), [25](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L25-L25), [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L26-L26), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L27-L27), [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L28-L28), [32](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L32-L32), [33](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L33-L33), [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L34-L34), [35](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L35-L35), [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L36-L36), [37](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L37-L37), [38](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L38-L38), [42](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L42-L42), [43](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L43-L43), [44](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L44-L44), [45](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L45-L45), [46](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L46-L46), [50](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L50-L50), [54](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L54-L54), [55](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L55-L55), [88](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L88-L88), [103](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L103-L103), [174](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L174-L174), [187](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L187-L187), [200](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L200-L200), [211](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L211-L211), [223](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L223-L226), [234](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L234-L241), [255](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L255-L262), [277](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L277-L283), [294](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L294-L300), [319](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L319-L319), [551](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L551-L551), [560](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L560-L560), [569](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L569-L573)

```solidity
File: src/LiquidityPool.sol

10       function permit(address owner, address spender, uint256 value, uint256 deadline, uint8 v, bytes32 r, bytes32 s)
11:          external;

12:      function PERMIT_TYPEHASH() external view returns (bytes32);

13:      function DOMAIN_SEPARATOR() external view returns (bytes32);

17:      function checkTransferRestriction(address from, address to, uint256 value) external view returns (bool);

21:      function processDeposit(address receiver, uint256 assets) external returns (uint256);

22:      function processMint(address receiver, uint256 shares) external returns (uint256);

23:      function processWithdraw(uint256 assets, address receiver, address owner) external returns (uint256);

24:      function processRedeem(uint256 shares, address receiver, address owner) external returns (uint256);

25:      function maxDeposit(address user, address _tranche) external view returns (uint256);

26:      function maxMint(address user, address _tranche) external view returns (uint256);

27:      function maxWithdraw(address user, address _tranche) external view returns (uint256);

28:      function maxRedeem(address user, address _tranche) external view returns (uint256);

29:      function totalAssets(uint256 totalSupply, address liquidityPool) external view returns (uint256);

30:      function convertToShares(uint256 assets, address liquidityPool) external view returns (uint256);

31:      function convertToAssets(uint256 shares, address liquidityPool) external view returns (uint256);

32:      function previewDeposit(address user, address liquidityPool, uint256 assets) external view returns (uint256);

33:      function previewMint(address user, address liquidityPool, uint256 shares) external view returns (uint256);

34:      function previewWithdraw(address user, address liquidityPool, uint256 assets) external view returns (uint256);

35:      function previewRedeem(address user, address liquidityPool, uint256 shares) external view returns (uint256);

36:      function requestRedeem(uint256 shares, address receiver) external;

37:      function requestDeposit(uint256 assets, address receiver) external;

38:      function collectDeposit(address receiver) external;

39:      function collectRedeem(address receiver) external;

40:      function decreaseDepositRequest(uint256 assets, address receiver) external;

41:      function decreaseRedeemRequest(uint256 shares, address receiver) external;

85:      constructor(uint64 poolId_, bytes16 trancheId_, address asset_, address share_, address investmentManager_) {

103:     function file(bytes32 what, address data) public auth {

271:     function name() public view returns (string memory) {

275:     function symbol() public view returns (string memory) {

279:     function decimals() public view returns (uint8) {

283:     function totalSupply() public view returns (uint256) {

287:     function balanceOf(address owner) public view returns (uint256) {

291:     function allowance(address owner, address spender) public view returns (uint256) {

295:     function transferFrom(address, address, uint256) public returns (bool) {

301:     function transfer(address, uint256) public returns (bool) {

307:     function approve(address, uint256) public returns (bool) {

313:     function mint(address, uint256) public auth {

318:     function burn(address, uint256) public auth {

324:     function updatePrice(uint128 price) public auth {

```
*GitHub*: [10](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L10-L11), [12](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L12-L12), [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L13-L13), [17](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L17-L17), [21](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L21-L21), [22](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L22-L22), [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L23-L23), [24](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L24-L24), [25](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L25-L25), [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L26-L26), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L27-L27), [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L28-L28), [29](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L29-L29), [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L30-L30), [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L31-L31), [32](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L32-L32), [33](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L33-L33), [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L34-L34), [35](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L35-L35), [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L36-L36), [37](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L37-L37), [38](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L38-L38), [39](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L39-L39), [40](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L40-L40), [41](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L41-L41), [85](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L85-L85), [103](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L103-L103), [271](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L271-L271), [275](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L275-L275), [279](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L279-L279), [283](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L283-L283), [287](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L287-L287), [291](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L291-L291), [295](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L295-L295), [301](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L301-L301), [307](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L307-L307), [313](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L313-L313), [318](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L318-L318), [324](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L324-L324)

```solidity
File: src/PoolManager.sol

12       function transferTrancheTokensToCentrifuge(
13           uint64 poolId,
14           bytes16 trancheId,
15           address sender,
16           bytes32 destinationAddress,
17           uint128 amount
18:      ) external;

19       function transferTrancheTokensToEVM(
20           uint64 poolId,
21           bytes16 trancheId,
22           address sender,
23           uint64 destinationChainId,
24           address destinationAddress,
25           uint128 amount
26:      ) external;

27:      function transfer(uint128 currency, address sender, bytes32 recipient, uint128 amount) external;

31:      function hasMember(address) external returns (bool);

35:      function liquidityPools(uint64 poolId, bytes16 trancheId, address currency) external returns (address);

36:      function getTrancheToken(uint64 _poolId, bytes16 _trancheId) external view returns (address);

37:      function userEscrow() external view returns (address);

41:      function approve(address token, address spender, uint256 value) external;

45:      function addLiquidityPool(address forwarder) external;

49:      function rely(address usr) external;

104:     constructor(address escrow_, address liquidityPoolFactory_, address trancheTokenFactory_) {

120:     function file(bytes32 what, address data) external auth {

128:     function transfer(address currencyAddress, bytes32 recipient, uint128 amount) public {

136      function transferTrancheTokensToCentrifuge(
137          uint64 poolId,
138          bytes16 trancheId,
139          bytes32 destinationAddress,
140          uint128 amount
141:     ) public {

149      function transferTrancheTokensToEVM(
150          uint64 poolId,
151          bytes16 trancheId,
152          uint64 destinationChainId,
153          address destinationAddress,
154          uint128 amount
155:     ) public {

214      function updateTrancheTokenMetadata(
215          uint64 poolId,
216          bytes16 trancheId,
217          string memory tokenName,
218          string memory tokenSymbol
219:     ) public onlyGateway {

227:     function updateMember(uint64 poolId, bytes16 trancheId, address user, uint64 validUntil) public onlyGateway {

257:     function handleTransfer(uint128 currency, address recipient, uint128 amount) public onlyGateway {

265      function handleTransferTrancheTokens(uint64 poolId, bytes16 trancheId, address destinationAddress, uint128 amount)
266          public
267          onlyGateway
268:     {

280:     function deployTranche(uint64 poolId, bytes16 trancheId) public returns (address) {

307:     function deployLiquidityPool(uint64 poolId, bytes16 trancheId, address currency) public returns (address) {

336:     function getTrancheToken(uint64 poolId, bytes16 trancheId) public view returns (address) {

341:     function getLiquidityPool(uint64 poolId, bytes16 trancheId, address currency) public view returns (address) {

345:     function isAllowedAsPoolCurrency(uint64 poolId, address currencyAddress) public view returns (bool) {

```
*GitHub*: [12](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L12-L18), [19](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L19-L26), [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L27-L27), [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L31-L31), [35](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L35-L35), [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L36-L36), [37](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L37-L37), [41](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L41-L41), [45](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L45-L45), [49](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L49-L49), [104](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L104-L104), [120](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L120-L120), [128](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L128-L128), [136](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L136-L141), [149](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L149-L155), [214](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L214-L219), [227](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L227-L227), [257](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L257-L257), [265](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L265-L268), [280](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L280-L280), [307](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L307-L307), [336](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L336-L336), [341](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L341-L341), [345](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L345-L345)

```solidity
File: src/Root.sol

7:       function rely(address) external;

8:       function deny(address) external;

34:      constructor(address _escrow, uint256 _delay) {

43:      function file(bytes32 what, uint256 data) external auth {

54:      function pause() external auth {

59:      function unpause() external auth {

70:      function cancelRely(address target) external auth {

75:      function executeScheduledRely(address target) public {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L7-L7), [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L8-L8), [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L34-L34), [43](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L43-L43), [54](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L54-L54), [59](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L59-L59), [70](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L70-L70), [75](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L75-L75)

```solidity
File: src/UserEscrow.sol

8:       function allowance(address owner, address spender) external view returns (uint256);

23:      constructor() {

29:      function transferIn(address token, address source, address destination, uint256 amount) external auth {

36:      function transferOut(address token, address destination, address receiver, uint256 amount) external auth {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L8-L8), [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L23-L23), [29](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L29-L29), [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L36-L36)

```solidity
File: src/admins/DelayedAdmin.sol

18:      constructor(address root_) {

26:      function pause() public auth {

30:      function unpause() public auth {

34:      function scheduleRely(address target) public auth {

38:      function cancelRely(address target) public auth {

```
*GitHub*: [18](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L18-L18), [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L26-L26), [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L30-L30), [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L34-L34), [38](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L38-L38)

```solidity
File: src/admins/PauseAdmin.sol

21:      constructor(address root_) {

34:      function addPauser(address user) external auth {

39:      function removePauser(address user) external auth {

45:      function pause() public canPause {

```
*GitHub*: [21](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L21-L21), [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L34-L34), [39](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L39-L39), [45](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L45-L45)

```solidity
File: src/gateway/Gateway.sol

8:       function updateTrancheTokenPrice(uint64 poolId, bytes16 trancheId, uint128 currencyId, uint128 price) external;

9        function handleExecutedDecreaseInvestOrder(
10           uint64 poolId,
11           bytes16 trancheId,
12           address investor,
13           uint128 currency,
14           uint128 currencyPayout
15:      ) external;

16       function handleExecutedDecreaseRedeemOrder(
17           uint64 poolId,
18           bytes16 trancheId,
19           address investor,
20           uint128 currency,
21           uint128 trancheTokensPayout
22:      ) external;

23       function handleExecutedCollectInvest(
24           uint64 poolId,
25           bytes16 trancheId,
26           address investor,
27           uint128 currency,
28           uint128 currencyPayout,
29           uint128 trancheTokensPayout
30:      ) external;

31       function handleExecutedCollectRedeem(
32           uint64 poolId,
33           bytes16 trancheId,
34           address investor,
35           uint128 currency,
36           uint128 currencyPayout,
37           uint128 trancheTokensPayout
38:      ) external;

42:      function addPool(uint64 poolId) external;

43:      function allowPoolCurrency(uint64 poolId, uint128 currency) external;

44       function addTranche(
45           uint64 poolId,
46           bytes16 trancheId,
47           string memory tokenName,
48           string memory tokenSymbol,
49           uint8 decimals
50:      ) external;

51:      function updateMember(uint64 poolId, bytes16 trancheId, address user, uint64 validUntil) external;

52       function updateTrancheTokenMetadata(
53           uint64 poolId,
54           bytes16 trancheId,
55           string memory tokenName,
56           string memory tokenSymbol
57:      ) external;

58:      function addCurrency(uint128 currency, address currencyAddress) external;

59:      function handleTransfer(uint128 currency, address recipient, uint128 amount) external;

60       function handleTransferTrancheTokens(uint64 poolId, bytes16 trancheId, address destinationAddress, uint128 amount)
61:          external;

65:      function send(bytes memory message) external;

69:      function rely(address usr) external;

73:      function paused() external returns (bool);

74:      function scheduleRely(address target) external;

75:      function cancelRely(address target) external;

98:      constructor(address root_, address investmentManager_, address poolManager_, address router_) {

130:     function file(bytes32 what, address data) public auth {

137:     function addIncomingRouter(address router) public auth {

142:     function removeIncomingRouter(address router) public auth {

147:     function updateOutgoingRouter(address router) public auth {

153      function transferTrancheTokensToCentrifuge(
154          uint64 poolId,
155          bytes16 trancheId,
156          address sender,
157          bytes32 destinationAddress,
158          uint128 amount
159:     ) public onlyPoolManager pauseable {

172      function transferTrancheTokensToEVM(
173          uint64 poolId,
174          bytes16 trancheId,
175          address sender,
176          uint64 destinationChainId,
177          address destinationAddress,
178          uint128 amount
179:     ) public onlyPoolManager pauseable {

192      function transfer(uint128 token, address sender, bytes32 receiver, uint128 amount)
193          public
194          onlyPoolManager
195          pauseable
196:     {

200      function increaseInvestOrder(
201          uint64 poolId,
202          bytes16 trancheId,
203          address investor,
204          uint128 currency,
205          uint128 currencyAmount
206:     ) public onlyInvestmentManager pauseable {

212      function decreaseInvestOrder(
213          uint64 poolId,
214          bytes16 trancheId,
215          address investor,
216          uint128 currency,
217          uint128 currencyAmount
218:     ) public onlyInvestmentManager pauseable {

224      function increaseRedeemOrder(
225          uint64 poolId,
226          bytes16 trancheId,
227          address investor,
228          uint128 currency,
229          uint128 trancheTokenAmount
230:     ) public onlyInvestmentManager pauseable {

238      function decreaseRedeemOrder(
239          uint64 poolId,
240          bytes16 trancheId,
241          address investor,
242          uint128 currency,
243          uint128 trancheTokenAmount
244:     ) public onlyInvestmentManager pauseable {

252      function collectInvest(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)
253          public
254          onlyInvestmentManager
255          pauseable
256:     {

260      function collectRedeem(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)
261          public
262          onlyInvestmentManager
263          pauseable
264:     {

268      function cancelInvestOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)
269          public
270          onlyInvestmentManager
271          pauseable
272:     {

276      function cancelRedeemOrder(uint64 poolId, bytes16 trancheId, address investor, uint128 currency)
277          public
278          onlyInvestmentManager
279          pauseable
280:     {

285:     function handle(bytes calldata message) external onlyIncomingRouter pauseable {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L8-L8), [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L9-L15), [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L16-L22), [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L23-L30), [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L31-L38), [42](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L42-L42), [43](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L43-L43), [44](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L44-L50), [51](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L51-L51), [52](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L52-L57), [58](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L58-L58), [59](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L59-L59), [60](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L60-L61), [65](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L65-L65), [69](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L69-L69), [73](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L73-L73), [74](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L74-L74), [75](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L75-L75), [98](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L98-L98), [130](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L130-L130), [137](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L137-L137), [142](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L142-L142), [147](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L147-L147), [153](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L153-L159), [172](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L172-L179), [192](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L192-L196), [200](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L200-L206), [212](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L212-L218), [224](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L224-L230), [238](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L238-L244), [252](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L252-L256), [260](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L260-L264), [268](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L268-L272), [276](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L276-L280), [285](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L285-L285)

```solidity
File: src/gateway/Messages.sol

836:     function formatDomain(Domain domain) public pure returns (bytes9) {

840:     function formatDomain(Domain domain, uint64 chainId) public pure returns (bytes9) {

```
*GitHub*: [836](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L836-L836), [840](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L840-L840)

```solidity
File: src/gateway/routers/axelar/Router.sol

7        function callContract(string calldata destinationChain, string calldata contractAddress, bytes calldata payload)
8:           external;

10       function validateContractCall(
11           bytes32 commandId,
12           string calldata sourceChain,
13           string calldata sourceAddress,
14           bytes32 payloadHash
15:      ) external returns (bool);

19:      function handle(bytes memory message) external;

36:      constructor(address axelarGateway_) {

62:      function file(bytes32 what, address data) external auth {

73       function execute(
74           bytes32 commandId,
75           string calldata sourceChain,
76           string calldata sourceAddress,
77           bytes calldata payload
78:      ) public onlyCentrifugeChainOrigin(sourceChain, sourceAddress) {

89:      function send(bytes calldata message) public onlyGateway {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L7-L8), [10](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L10-L15), [19](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L19-L19), [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L36-L36), [62](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L62-L62), [73](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L73-L78), [89](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L89-L89)

```solidity
File: src/token/ERC20.sol

9:       function isValidSignature(bytes32, bytes memory) external view returns (bytes4);

42:      constructor(uint8 decimals_) {

57:      function rely(address user) external auth {

62:      function deny(address user) external auth {

79:      function DOMAIN_SEPARATOR() external view returns (bytes32) {

83:      function file(bytes32 what, string memory data) external auth {

91:      function transfer(address to, uint256 value) public virtual returns (bool) {

106:     function transferFrom(address from, address to, uint256 value) public virtual returns (bool) {

131:     function approve(address spender, uint256 value) external returns (bool) {

139:     function increaseAllowance(address spender, uint256 addedValue) external returns (bool) {

148:     function decreaseAllowance(address spender, uint256 subtractedValue) external returns (bool) {

162:     function mint(address to, uint256 value) public virtual auth {

172:     function burn(address from, uint256 value) external auth {

216:     function permit(address owner, address spender, uint256 value, uint256 deadline, bytes memory signature) public {

239      function permit(address owner, address spender, uint256 value, uint256 deadline, uint8 v, bytes32 r, bytes32 s)
240          external
241:     {

```
*GitHub*: [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L9-L9), [42](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L42-L42), [57](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L57-L57), [62](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L62-L62), [79](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L79-L79), [83](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L83-L83), [91](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L91-L91), [106](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L106-L106), [131](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L131-L131), [139](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L139-L139), [148](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L148-L148), [162](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L162-L162), [172](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L172-L172), [216](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L216-L216), [239](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L239-L241)

```solidity
File: src/token/RestrictionManager.sol

7:       function updateMember(address user, uint256 validUntil) external;

8:       function members(address user) external view returns (uint256);

9:       function hasMember(address user) external view returns (bool);

22:      constructor() {

28:      function detectTransferRestriction(address from, address to, uint256 value) public view returns (uint8) {

36:      function messageForTransferRestriction(uint8 restrictionCode) public view returns (string memory) {

45:      function member(address user) public view {

49:      function hasMember(address user) public view returns (bool) {

57:      function updateMember(address user, uint256 validUntil) public auth {

62:      function updateMembers(address[] memory users, uint256 validUntil) public auth {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L7-L7), [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L8-L8), [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L9-L9), [22](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L22-L22), [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L28-L28), [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L36-L36), [45](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L45-L45), [49](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L49-L49), [57](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L57-L57), [62](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L62-L62)

```solidity
File: src/token/Tranche.sol

8:       function file(bytes32 what, string memory data) external;

9:       function restrictionManager() external view returns (address);

13:      function detectTransferRestriction(address from, address to, uint256 value) external view returns (uint8);

14:      function messageForTransferRestriction(uint8 restrictionCode) external view returns (string memory);

15:      function SUCCESS_CODE() external view returns (uint8);

33:      constructor(uint8 decimals_) ERC20(decimals_) {}

42:      function file(bytes32 what, address data) public auth {

48:      function addLiquidityPool(address liquidityPool) public auth {

53:      function removeLiquidityPool(address liquidityPool) public auth {

59:      function transfer(address to, uint256 value) public override restricted(_msgSender(), to, value) returns (bool) {

63       function transferFrom(address from, address to, uint256 value)
64           public
65           override
66           restricted(from, to, value)
67           returns (bool)
68:      {

72:      function mint(address to, uint256 value) public override restricted(_msgSender(), to, value) {

76:      function detectTransferRestriction(address from, address to, uint256 value) public view returns (uint8) {

80:      function checkTransferRestriction(address from, address to, uint256 value) public view returns (bool) {

84:      function messageForTransferRestriction(uint8 restrictionCode) public view returns (string memory) {

88:      function SUCCESS_CODE() public view returns (uint8) {

93:      function isTrustedForwarder(address forwarder) public view returns (bool) {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L8-L8), [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L9-L9), [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L13-L13), [14](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L14-L14), [15](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L15-L15), [33](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L33-L33), [42](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L42-L42), [48](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L48-L48), [53](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L53-L53), [59](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L59-L59), [63](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L63-L68), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L72-L72), [76](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L76-L76), [80](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L80-L80), [84](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L84-L84), [88](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L88-L88), [93](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L93-L93)

```solidity
File: src/util/Factory.sol

10:      function escrow() external view returns (address);

14       function newLiquidityPool(
15           uint64 poolId,
16           bytes16 trancheId,
17           address currency,
18           address trancheToken,
19           address investmentManager,
20           address[] calldata wards
21:      ) external returns (address);

29:      constructor(address _root) {

36       function newLiquidityPool(
37           uint64 poolId,
38           bytes16 trancheId,
39           address currency,
40           address trancheToken,
41           address investmentManager,
42           address[] calldata wards
43:      ) public auth returns (address) {

56       function newTrancheToken(
57           uint64 poolId,
58           bytes16 trancheId,
59           string memory name,
60           string memory symbol,
61           uint8 decimals,
62           address[] calldata trancheTokenWards,
63           address[] calldata restrictionManagerWards
64:      ) external returns (address);

74:      constructor(address _root) {

81       function newTrancheToken(
82           uint64 poolId,
83           bytes16 trancheId,
84           string memory name,
85           string memory symbol,
86           uint8 decimals,
87           address[] calldata trancheTokenWards,
88           address[] calldata restrictionManagerWards
89:      ) public auth returns (address) {

```
*GitHub*: [10](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L10-L10), [14](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L14-L21), [29](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L29-L29), [36](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L36-L43), [56](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L56-L64), [74](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L74-L74), [81](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L81-L89)

</details>




### [N&#x2011;54] Function names should use lowerCamelCase
According to the Solidity [style guide](https://docs.soliditylang.org/en/latest/style-guide.html#function-names) function names should be in `mixedCase` (lowerCamelCase)

*There are 2 instances of this issue:*

```solidity
File: src/token/Tranche.sol

15:      function SUCCESS_CODE() external view returns (uint8);

88:      function SUCCESS_CODE() public view returns (uint8) {

```
*GitHub*: [15](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L15-L15), [88](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L88-L88)


### [N&#x2011;55] Constants in comparisons should appear on the left side
Doing so will prevent [typo bugs](https://www.moserware.com/2008/01/constants-on-left-are-better-but-this.html)

*There are 57 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/InvestmentManager.sol

104:         if (what == "gateway") gateway = GatewayLike(data);

105:         else if (what == "poolManager") poolManager = PoolManagerLike(data);

127:         if (_currencyAmount == 0) {

159:         if (_trancheTokenAmount == 0) {

242:         require(currencyPayout != 0, "InvestmentManager/zero-invest");

263:         require(trancheTokensPayout != 0, "InvestmentManager/zero-redeem");

284:         require(currencyPayout != 0, "InvestmentManager/zero-payout");

301:         require(trancheTokenPayout != 0, "InvestmentManager/zero-payout");

377:         if (depositPrice == 0) return 0;

390:         if (depositPrice == 0) return 0;

403:         if (redeemPrice == 0) return 0;

416:         if (redeemPrice == 0) return 0;

431:             (_currencyAmount <= orderbook[user][liquidityPool].maxDeposit && _currencyAmount != 0),

436:         require(depositPrice != 0, "LiquidityPool/deposit-token-price-0");

455:             (_trancheTokenAmount <= orderbook[user][liquidityPool].maxMint && _trancheTokenAmount != 0),

460:         require(depositPrice != 0, "LiquidityPool/deposit-token-price-0");

497:             (_trancheTokenAmount <= orderbook[user][liquidityPool].maxRedeem && _trancheTokenAmount != 0),

502:         require(redeemPrice != 0, "LiquidityPool/redeem-token-price-0");

523:             (_currencyAmount <= orderbook[user][liquidityPool].maxWithdraw && _currencyAmount != 0),

528:         require(redeemPrice != 0, "LiquidityPool/redeem-token-price-0");

553:         if (lpValues.maxMint == 0) {

562:         if (lpValues.maxRedeem == 0) {

```
*GitHub*: [104](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L104-L104), [105](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L105-L105), [127](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L127-L127), [159](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L159-L159), [242](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L242-L242), [263](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L263-L263), [284](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L284-L284), [301](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L301-L301), [377](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L377-L377), [390](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L390-L390), [403](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L403-L403), [416](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L416-L416), [431](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L431-L431), [436](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L436-L436), [455](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L455-L455), [460](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L460-L460), [497](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L497-L497), [502](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L502-L502), [523](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L523-L523), [528](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L528-L528), [553](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L553-L553), [562](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L562-L562)

```solidity
File: src/LiquidityPool.sol

104:         if (what == "investmentManager") investmentManager = InvestmentManagerLike(data);

```
*GitHub*: [104](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L104-L104)

```solidity
File: src/PoolManager.sol

121:         if (what == "gateway") gateway = GatewayLike(data);

122:         else if (what == "investmentManager") investmentManager = InvestmentManagerLike(data);

130:         require(currency != 0, "PoolManager/unknown-currency");

170:         require(pool.createdAt == 0, "PoolManager/pool-already-added");

181:         require(pool.createdAt != 0, "PoolManager/invalid-pool");

200:         require(pool.createdAt != 0, "PoolManager/invalid-pool");

202:         require(tranche.createdAt == 0, "PoolManager/tranche-already-exists");

240:         require(currency != 0, "PoolManager/currency-id-has-to-be-greater-than-0");

242:         require(currencyAddressToId[currencyAddress] == 0, "PoolManager/currency-address-in-use");

283:         require(tranche.createdAt != 0, "PoolManager/tranche-not-added");

314:         require(pools[poolId].createdAt != 0, "PoolManager/pool-does-not-exist");

347:         require(currency != 0, "PoolManager/unknown-currency"); // Currency index on the Centrifuge side should start at 1

```
*GitHub*: [121](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L121-L121), [122](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L122-L122), [130](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L130-L130), [170](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L170-L170), [181](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L181-L181), [200](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L200-L200), [202](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L202-L202), [240](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L240-L240), [242](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L242-L242), [283](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L283-L283), [314](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L314-L314), [347](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L347-L347)

```solidity
File: src/Root.sol

44:          if (what == "delay") {

76:          require(schedule[target] != 0, "Root/target-not-scheduled");

```
*GitHub*: [44](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L44-L44), [76](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L76-L76)

```solidity
File: src/admins/PauseAdmin.sol

29:          require(pausers[msg.sender] == 1, "PauseAdmin/not-authorized-to-pause");

```
*GitHub*: [29](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L29-L29)

```solidity
File: src/gateway/Gateway.sol

131:         if (what == "poolManager") poolManager = PoolManagerLike(data);

132:         else if (what == "investmentManager") investmentManager = InvestmentManagerLike(data);

```
*GitHub*: [131](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L131-L131), [132](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L132-L132)

```solidity
File: src/gateway/Messages.sol

860:         require(_bytes128.length == 128, "Input should be 128 bytes");

863:         while (i < 128 && _bytes128[i] != 0) {

878:         if (tempEmptyStringTest.length == 0) {

889:         while (i < 32 && _bytes32[i] != 0) {

893:         for (i = 0; i < 32 && _bytes32[i] != 0; i++) {

```
*GitHub*: [860](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L860-L860), [863](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L863-L863), [878](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L878-L878), [889](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L889-L889), [893](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L893-L893)

```solidity
File: src/gateway/routers/axelar/Router.sol

63:          if (what == "gateway") {

```
*GitHub*: [63](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L63-L63)

```solidity
File: src/token/ERC20.sol

53:          require(wards[_msgSender()] == 1, "Auth/not-authorized");

84:          if (what == "name") name = data;

85:          else if (what == "symbol") symbol = data;

197:         if (signature.length == 65) {

213:         return (success && result.length == 32 && abi.decode(result, (bytes4)) == IERC1271.isValidSignature.selector);

```
*GitHub*: [53](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L53-L53), [84](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L84-L84), [85](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L85-L85), [197](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L197-L197), [213](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L213-L213)

```solidity
File: src/token/Tranche.sol

43:          if (what == "restrictionManager") restrictionManager = ERC1404Like(data);

104:         if (isTrustedForwarder(msg.sender) && msg.data.length >= 20) {

```
*GitHub*: [43](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L43-L43), [104](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L104-L104)

```solidity
File: src/util/Auth.sol

27:          require(wards[msg.sender] == 1, "Auth/not-authorized");

```
*GitHub*: [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L27-L27)

```solidity
File: src/util/SafeTransferLib.sol

18:          require(success && (data.length == 0 || abi.decode(data, (bool))), "SafeTransferLib/safe-transfer-from-failed");

28:          require(success && (data.length == 0 || abi.decode(data, (bool))), "SafeTransferLib/safe-transfer-failed");

38:          require(success && (data.length == 0 || abi.decode(data, (bool))), "SafeTransferLib/safe-approve-failed");

```
*GitHub*: [18](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L18-L18), [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L28-L28), [38](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L38-L38)

</details>




### [N&#x2011;56] Events should use parameters to convey information
For example, rather than using `event Paused()` and `event Unpaused()`, use `event PauseState(address indexed whoChangedIt, bool wasPaused, bool isNowPaused)`

*There are 2 instances of this issue:*

```solidity
File: src/Root.sol

27:      event Pause();

28:      event Unpause();

```
*GitHub*: [27](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L27-L27), [28](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L28-L28)


### [N&#x2011;57] Contract declarations should have NatSpec `@author` annotations


*There are 51 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/Escrow.sol

7:   interface ApproveLike {

14:  contract Escrow is Auth {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L7-L7), [14](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L14-L14)

```solidity
File: src/InvestmentManager.sol

8:   interface GatewayLike {

23:  interface ERC20Like {

31:  interface LiquidityPoolLike is ERC20Like {

41:  interface PoolManagerLike {

49:  interface EscrowLike {

53:  interface UserEscrowLike {

69:  contract InvestmentManager is Auth {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L8-L8), [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L23-L23), [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L31-L31), [41](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L41-L41), [49](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L49-L49), [53](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L53-L53), [69](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L69-L69)

```solidity
File: src/LiquidityPool.sol

9:   interface ERC20PermitLike {

16:  interface TrancheTokenLike is IERC20, ERC20PermitLike {

20:  interface InvestmentManagerLike {

52:  contract LiquidityPool is Auth, IERC4626 {

```
*GitHub*: [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L9-L9), [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L16-L16), [20](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L20-L20), [52](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L52-L52)

```solidity
File: src/PoolManager.sol

11:  interface GatewayLike {

30:  interface LiquidityPoolLike {

34:  interface InvestmentManagerLike {

40:  interface EscrowLike {

44:  interface ERC2771Like {

48:  interface AuthLike {

78:  contract PoolManager is Auth {

```
*GitHub*: [11](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L11-L11), [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L30-L30), [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L34-L34), [40](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L40-L40), [44](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L44-L44), [48](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L48-L48), [78](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L78-L78)

```solidity
File: src/Root.sol

6:   interface AuthLike {

15   contract Root is Auth {
16:      /// @dev To prevent filing a delay that would block any updates indefinitely

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L6-L6), [15](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L15-L16)

```solidity
File: src/UserEscrow.sol

7:   interface ERC20Like {

15   contract UserEscrow is Auth {
16:      /// @dev Map by token and destination

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L7-L7), [15](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L15-L16)

```solidity
File: src/admins/DelayedAdmin.sol

12:  contract DelayedAdmin is Auth {

```
*GitHub*: [12](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/DelayedAdmin.sol#L12-L12)

```solidity
File: src/admins/PauseAdmin.sol

10:  contract PauseAdmin is Auth {

```
*GitHub*: [10](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/admins/PauseAdmin.sol#L10-L10)

```solidity
File: src/gateway/Gateway.sol

7:   interface InvestmentManagerLike {

41:  interface PoolManagerLike {

64:  interface RouterLike {

68:  interface AuthLike {

72:  interface RootLike {

84:  contract Gateway is Auth {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L7-L7), [41](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L41-L41), [64](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L64-L64), [68](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L68-L68), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L72-L72), [84](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L84-L84)

```solidity
File: src/gateway/Messages.sol

8:   library Messages {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Messages.sol#L8-L8)

```solidity
File: src/gateway/routers/axelar/Router.sol

6:   interface AxelarGatewayLike {

18:  interface GatewayLike {

24:  contract AxelarRouter is Auth {

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L6-L6), [18](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L18-L18), [24](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L24-L24)

```solidity
File: src/token/ERC20.sol

8:   interface IERC1271 {

16:  contract ERC20 is Context {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L8-L8), [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L16-L16)

```solidity
File: src/token/RestrictionManager.sol

6:   interface MemberlistLike {

14:  contract RestrictionManager is Auth {

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L6-L6), [14](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L14-L14)

```solidity
File: src/token/Tranche.sol

7:   interface TrancheTokenLike is IERC20 {

12:  interface ERC1404Like {

23:  contract TrancheToken is ERC20, ERC1404Like {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L7-L7), [12](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L12-L12), [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L23-L23)

```solidity
File: src/util/Auth.sol

7:   contract Auth {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Auth.sol#L7-L7)

```solidity
File: src/util/Context.sol

12:  abstract contract Context {

```
*GitHub*: [12](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Context.sol#L12-L12)

```solidity
File: src/util/Factory.sol

9:   interface RootLike {

13:  interface LiquidityPoolFactoryLike {

26:  contract LiquidityPoolFactory is Auth {

55:  interface TrancheTokenFactoryLike {

71:  contract TrancheTokenFactory is Auth {

```
*GitHub*: [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L9-L9), [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L13-L13), [26](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L26-L26), [55](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L55-L55), [71](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L71-L71)

```solidity
File: src/util/SafeTransferLib.sol

8    library SafeTransferLib {
9        /// @notice Transfers tokens from the targeted address to the given destination
10       /// @notice Errors if transfer fails
11       /// @param token The contract address of the token to be transferred
12       /// @param from The originating address from which the tokens will be transferred
13       /// @param to The destination address of the transfer
14:      /// @param value The amount to be transferred

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/SafeTransferLib.sol#L8-L14)

</details>




### [N&#x2011;58] Contract declarations should have NatSpec `@title` annotations


*There are 32 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/Escrow.sol

7:   interface ApproveLike {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L7-L7)

```solidity
File: src/InvestmentManager.sol

8:   interface GatewayLike {

23:  interface ERC20Like {

31:  interface LiquidityPoolLike is ERC20Like {

41:  interface PoolManagerLike {

49:  interface EscrowLike {

53:  interface UserEscrowLike {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L8-L8), [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L23-L23), [31](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L31-L31), [41](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L41-L41), [49](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L49-L49), [53](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L53-L53)

```solidity
File: src/LiquidityPool.sol

9:   interface ERC20PermitLike {

16:  interface TrancheTokenLike is IERC20, ERC20PermitLike {

20:  interface InvestmentManagerLike {

```
*GitHub*: [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L9-L9), [16](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L16-L16), [20](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L20-L20)

```solidity
File: src/PoolManager.sol

11:  interface GatewayLike {

30:  interface LiquidityPoolLike {

34:  interface InvestmentManagerLike {

40:  interface EscrowLike {

44:  interface ERC2771Like {

48:  interface AuthLike {

```
*GitHub*: [11](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L11-L11), [30](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L30-L30), [34](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L34-L34), [40](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L40-L40), [44](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L44-L44), [48](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L48-L48)

```solidity
File: src/Root.sol

6:   interface AuthLike {

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L6-L6)

```solidity
File: src/UserEscrow.sol

7:   interface ERC20Like {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/UserEscrow.sol#L7-L7)

```solidity
File: src/gateway/Gateway.sol

7:   interface InvestmentManagerLike {

41:  interface PoolManagerLike {

64:  interface RouterLike {

68:  interface AuthLike {

72:  interface RootLike {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L7-L7), [41](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L41-L41), [64](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L64-L64), [68](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L68-L68), [72](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/Gateway.sol#L72-L72)

```solidity
File: src/gateway/routers/axelar/Router.sol

6:   interface AxelarGatewayLike {

18:  interface GatewayLike {

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L6-L6), [18](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/gateway/routers/axelar/Router.sol#L18-L18)

```solidity
File: src/token/ERC20.sol

8:   interface IERC1271 {

```
*GitHub*: [8](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L8-L8)

```solidity
File: src/token/RestrictionManager.sol

6:   interface MemberlistLike {

```
*GitHub*: [6](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/RestrictionManager.sol#L6-L6)

```solidity
File: src/token/Tranche.sol

7:   interface TrancheTokenLike is IERC20 {

12:  interface ERC1404Like {

```
*GitHub*: [7](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L7-L7), [12](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L12-L12)

```solidity
File: src/util/Factory.sol

9:   interface RootLike {

13:  interface LiquidityPoolFactoryLike {

55:  interface TrancheTokenFactoryLike {

```
*GitHub*: [9](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L9-L9), [13](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L13-L13), [55](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/util/Factory.sol#L55-L55)

</details>




### [N&#x2011;59] Empty function body
Consider adding a comment about why the function body is empty

*There is one instance of this issue:*

```solidity
File: src/token/Tranche.sol

33:      constructor(uint8 decimals_) ERC20(decimals_) {}

```
*GitHub*: [33](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/Tranche.sol#L33-L33)


### [N&#x2011;60] Use `bytes.concat()` on bytes instead of `abi.encodePacked()` for clearer semantic meaning
Starting with version 0.8.4, Solidity has the `bytes.concat()` function, which allows one to concatenate a list of bytes/strings, without extra padding. Using this function rather than `abi.encodePacked()` makes the intended operation more clear, leading to less reviewer confusion.

*There is one instance of this issue:*

```solidity
File: src/token/ERC20.sol

226              abi.encodePacked(
227                  "\x19\x01",
228                  block.chainid == deploymentChainId ? _DOMAIN_SEPARATOR : _calculateDomainSeparator(block.chainid),
229                  keccak256(abi.encode(PERMIT_TYPEHASH, owner, spender, value, nonce, deadline))
230:             )

```
*GitHub*: [226](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L226-L230)


### [N&#x2011;61] `if`-statement can be converted to a ternary
The code can be made more compact while also increasing readability by converting the following `if`-statements to ternaries (e.g. `foo += (x > y) ? a : b`)

*There are 4 instances of this issue:*

```solidity
File: src/InvestmentManager.sol

623          if (lpValues.maxDeposit < _currency) {
624              lpValues.maxDeposit = 0;
625          } else {
626              lpValues.maxDeposit = lpValues.maxDeposit - _currency;
627:         }

628          if (lpValues.maxMint < trancheTokens) {
629              lpValues.maxMint = 0;
630          } else {
631              lpValues.maxMint = lpValues.maxMint - trancheTokens;
632:         }

639          if (lpValues.maxWithdraw < _currency) {
640              lpValues.maxWithdraw = 0;
641          } else {
642              lpValues.maxWithdraw = lpValues.maxWithdraw - _currency;
643:         }

644          if (lpValues.maxRedeem < trancheTokens) {
645              lpValues.maxRedeem = 0;
646          } else {
647              lpValues.maxRedeem = lpValues.maxRedeem - trancheTokens;
648:         }

```
*GitHub*: [623](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L623-L627), [628](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L628-L632), [639](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L639-L643), [644](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L644-L648)


### [N&#x2011;62] Overflows in unchecked blocks
While integers with a large number of bits are unlikely to overflow on human time scales, it is not strictly correct to use an `unchecked` block around them, because _eventually_ they will overflow, and `unchecked` blocks are meant for cases where it's mathematically impossible for an operation to trigger an overflow (e.g. a prior `require()` statement prevents the overflow case)

*There is one instance of this issue:*

```solidity
File: src/token/ERC20.sol

222:             nonce = nonces[owner]++;

```
*GitHub*: [222](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L222-L222)


### [N&#x2011;63] Expressions for constant values should use `immutable` rather than `constant`
While it does not save gas for some simple binary expressions because the compiler knows that developers often make this mistake, it's still best to use the right tool for the task at hand. There is a difference between `constant` variables and `immutable` variables, and they should each be used in their appropriate contexts. `constants` should be used for literal values written into the code, and `immutable` variables should be used for expressions, or values calculated in, or passed into the constructor.

*There is one instance of this issue:*

```solidity
File: src/token/ERC20.sol

32       bytes32 public constant PERMIT_TYPEHASH =
33:          keccak256("Permit(address owner,address spender,uint256 value,uint256 nonce,uint256 deadline)");

```
*GitHub*: [32](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/token/ERC20.sol#L32-L33)


### [N&#x2011;64] Contract should expose an `interface`
The `contract`s should expose an `interface` so that other projects can more easily integrate with it, without having to develop their own non-standard variants.

*There are 152 instances of this issue:*

<details>
<summary>see instances</summary>


```solidity
File: src/Escrow.sol

23:      function approve(address token, address spender, uint256 value) external auth {

```
*GitHub*: [23](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Escrow.sol#L23-L23)

```solidity
File: src/InvestmentManager.sol

103:     function file(bytes32 what, address data) external auth {

117:     function requestDeposit(uint256 currencyAmount, address user) public auth {

148:     function requestRedeem(uint256 trancheTokenAmount, address user) public auth {

174:     function decreaseDepositRequest(uint256 _currencyAmount, address user) public auth {

187:     function decreaseRedeemRequest(uint256 _trancheTokenAmount, address user) public auth {

200:     function collectDeposit(address user) public auth {

211:     function collectRedeem(address user) public auth {

223      function updateTrancheTokenPrice(uint64 poolId, bytes16 trancheId, uint128 currencyId, uint128 price)
224          public
225          onlyGateway
226:     {

234      function handleExecutedCollectInvest(
235          uint64 poolId,
236          bytes16 trancheId,
237          address recipient,
238          uint128 currency,
239          uint128 currencyPayout,
240          uint128 trancheTokensPayout
241:     ) public onlyGateway {

255      function handleExecutedCollectRedeem(
256          uint64 poolId,
257          bytes16 trancheId,
258          address recipient,
259          uint128 currency,
260          uint128 currencyPayout,
261          uint128 trancheTokensPayout
262:     ) public onlyGateway {

277      function handleExecutedDecreaseInvestOrder(
278          uint64 poolId,
279          bytes16 trancheId,
280          address user,
281          uint128 currency,
282          uint128 currencyPayout
283:     ) public onlyGateway {

294      function handleExecutedDecreaseRedeemOrder(
295          uint64 poolId,
296          bytes16 trancheId,
297          address user,
298          uint128 currency,
299          uint128 trancheTokenPayout
300:     ) public onlyGateway {

319:     function totalAssets(uint256 totalSupply, address liquidityPool) public view returns (uint256 _totalAssets) {

325:     function convertToShares(uint256 _assets, address liquidityPool) public view auth returns (uint256 shares) {

338:     function convertToAssets(uint256 _shares, address liquidityPool) public view auth returns (uint256 assets) {

350:     function maxDeposit(address user, address liquidityPool) public view returns (uint256 currencyAmount) {

355:     function maxMint(address user, address liquidityPool) public view returns (uint256 trancheTokenAmount) {

360:     function maxWithdraw(address user, address liquidityPool) public view returns (uint256 currencyAmount) {

365:     function maxRedeem(address user, address liquidityPool) public view returns (uint256 trancheTokenAmount) {

370      function previewDeposit(address user, address liquidityPool, uint256 _currencyAmount)
371          public
372          view
373          returns (uint256 trancheTokenAmount)
374:     {

383      function previewMint(address user, address liquidityPool, uint256 _trancheTokenAmount)
384          public
385          view
386          returns (uint256 currencyAmount)
387:     {

396      function previewWithdraw(address user, address liquidityPool, uint256 _currencyAmount)
397          public
398          view
399          returns (uint256 trancheTokenAmount)
400:     {

409      function previewRedeem(address user, address liquidityPool, uint256 _trancheTokenAmount)
410          public
411          view
412          returns (uint256 currencyAmount)
413:     {

427:     function processDeposit(address user, uint256 currencyAmount) public auth returns (uint256 trancheTokenAmount) {

451:     function processMint(address user, uint256 trancheTokenAmount) public auth returns (uint256 currencyAmount) {

489      function processRedeem(uint256 trancheTokenAmount, address receiver, address user)
490          public
491          auth
492          returns (uint256 currencyAmount)
493:     {

515      function processWithdraw(uint256 currencyAmount, address receiver, address user)
516          public
517          auth
518          returns (uint256 trancheTokenAmount)
519:     {

551:     function calculateDepositPrice(address user, address liquidityPool) public view returns (uint256 depositPrice) {

560:     function calculateRedeemPrice(address user, address liquidityPool) public view returns (uint256 redeemPrice) {

569      function _calculatePrice(uint128 currencyAmount, uint128 trancheTokenAmount, address liquidityPool)
570          public
571          view
572          returns (uint256 depositPrice)
573:     {

```
*GitHub*: [103](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L103-L103), [117](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L117-L117), [148](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L148-L148), [174](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L174-L174), [187](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L187-L187), [200](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L200-L200), [211](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L211-L211), [223](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L223-L226), [234](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L234-L241), [255](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L255-L262), [277](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L277-L283), [294](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L294-L300), [319](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L319-L319), [325](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L325-L325), [338](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L338-L338), [350](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L350-L350), [355](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L355-L355), [360](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L360-L360), [365](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L365-L365), [370](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L370-L374), [383](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L383-L387), [396](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L396-L400), [409](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L409-L413), [427](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L427-L427), [451](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L451-L451), [489](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L489-L493), [515](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L515-L519), [551](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L551-L551), [560](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L560-L560), [569](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/InvestmentManager.sol#L569-L573)

```solidity
File: src/LiquidityPool.sol

103:     function file(bytes32 what, address data) public auth {

111:     function totalAssets() public view returns (uint256) {

118:     function convertToShares(uint256 assets) public view returns (uint256 shares) {

125:     function convertToAssets(uint256 shares) public view returns (uint256 assets) {

130:     function maxDeposit(address receiver) public view returns (uint256) {

135:     function previewDeposit(uint256 assets) public view returns (uint256 shares) {

141:     function deposit(uint256 assets, address receiver) public returns (uint256 shares) {

148      function mint(uint256 shares, address receiver) public returns (uint256 assets) {
149:         // require(receiver == msg.sender, "LiquidityPool/not-authorized-to-mint");

155:     function maxMint(address receiver) external view returns (uint256 maxShares) {

160:     function previewMint(uint256 shares) external view returns (uint256 assets) {

165:     function maxWithdraw(address receiver) public view returns (uint256 maxAssets) {

170:     function previewWithdraw(uint256 assets) public view returns (uint256 shares) {

176      function withdraw(uint256 assets, address receiver, address owner)
177          public
178          withApproval(owner)
179          returns (uint256 shares)
180:     {

187:     function maxRedeem(address owner) public view returns (uint256 maxShares) {

192:     function previewRedeem(uint256 shares) public view returns (uint256 assets) {

200      function redeem(uint256 shares, address receiver, address owner)
201          public
202          withApproval(owner)
203          returns (uint256 assets)
204:     {

214:     function requestDeposit(uint256 assets, address owner) public withApproval(owner) {

220      function requestDepositWithPermit(uint256 assets, address owner, uint256 deadline, uint8 v, bytes32 r, bytes32 s)
221          public
222:     {

231:     function requestRedeem(uint256 shares, address owner) public withApproval(owner) {

237      function requestRedeemWithPermit(uint256 shares, address owner, uint256 deadline, uint8 v, bytes32 r, bytes32 s)
238          public
239:     {

247:     function decreaseDepositRequest(uint256 assets, address owner) public withApproval(owner) {

253:     function decreaseRedeemRequest(uint256 shares, address owner) public withApproval(owner) {

259:     function collectDeposit(address receiver) public {

265:     function collectRedeem(address receiver) public {

271:     function name() public view returns (string memory) {

275:     function symbol() public view returns (string memory) {

279:     function decimals() public view returns (uint8) {

283:     function totalSupply() public view returns (uint256) {

287:     function balanceOf(address owner) public view returns (uint256) {

291:     function allowance(address owner, address spender) public view returns (uint256) {

295:     function transferFrom(address, address, uint256) public returns (bool) {

301:     function transfer(address, uint256) public returns (bool) {

307:     function approve(address, uint256) public returns (bool) {

313:     function mint(address, uint256) public auth {

318:     function burn(address, uint256) public auth {

324:     function updatePrice(uint128 price) public auth {

332:     function checkTransferRestriction(address from, address to, uint256 value) public view returns (bool) {

```
*GitHub*: [103](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L103-L103), [111](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L111-L111), [118](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L118-L118), [125](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L125-L125), [130](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L130-L130), [135](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L135-L135), [141](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L141-L141), [148](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L148-L149), [155](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L155-L155), [160](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L160-L160), [165](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L165-L165), [170](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L170-L170), [176](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L176-L180), [187](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L187-L187), [192](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L192-L192), [200](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L200-L204), [214](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L214-L214), [220](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L220-L222), [231](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L231-L231), [237](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L237-L239), [247](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L247-L247), [253](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L253-L253), [259](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L259-L259), [265](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L265-L265), [271](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L271-L271), [275](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L275-L275), [279](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L279-L279), [283](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L283-L283), [287](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L287-L287), [291](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L291-L291), [295](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L295-L295), [301](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L301-L301), [307](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L307-L307), [313](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L313-L313), [318](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L318-L318), [324](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L324-L324), [332](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/LiquidityPool.sol#L332-L332)

```solidity
File: src/PoolManager.sol

120:     function file(bytes32 what, address data) external auth {

128:     function transfer(address currencyAddress, bytes32 recipient, uint128 amount) public {

136      function transferTrancheTokensToCentrifuge(
137          uint64 poolId,
138          bytes16 trancheId,
139          bytes32 destinationAddress,
140          uint128 amount
141:     ) public {

149      function transferTrancheTokensToEVM(
150          uint64 poolId,
151          bytes16 trancheId,
152          uint64 destinationChainId,
153          address destinationAddress,
154          uint128 amount
155:     ) public {

168:     function addPool(uint64 poolId) public onlyGateway {

179:     function allowPoolCurrency(uint64 poolId, uint128 currency) public onlyGateway {

192      function addTranche(
193          uint64 poolId,
194          bytes16 trancheId,
195          string memory tokenName,
196          string memory tokenSymbol,
197          uint8 decimals
198:     ) public onlyGateway {

214      function updateTrancheTokenMetadata(
215          uint64 poolId,
216          bytes16 trancheId,
217          string memory tokenName,
218          string memory tokenSymbol
219:     ) public onlyGateway {

227:     function updateMember(uint64 poolId, bytes16 trancheId, address user, uint64 validUntil) public onlyGateway {

238:     function addCurrency(uint128 currency, address currencyAddress) public onlyGateway {

257:     function handleTransfer(uint128 currency, address recipient, uint128 amount) public onlyGateway {

265      function handleTransferTrancheTokens(uint64 poolId, bytes16 trancheId, address destinationAddress, uint128 amount)
266          public
267          onlyGateway
268:     {

280:     function deployTranche(uint64 poolId, bytes16 trancheId) public returns (address) {

307:     function deployLiquidityPool(uint64 poolId, bytes16 trancheId, address currency) public returns (address) {

336:     function getTrancheToken(uint64 poolId, bytes16 trancheId) public view returns (address) {

341:     function getLiquidityPool(uint64 poolId, bytes16 trancheId, address currency) public view returns (address) {

345:     function isAllowedAsPoolCurrency(uint64 poolId, address currencyAddress) public view returns (bool) {

```
*GitHub*: [120](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L120-L120), [128](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L128-L128), [136](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L136-L141), [149](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L149-L155), [168](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L168-L168), [179](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L179-L179), [192](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L192-L198), [214](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L214-L219), [227](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L227-L227), [238](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L238-L238), [257](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L257-L257), [265](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L265-L268), [280](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L280-L280), [307](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L307-L307), [336](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L336-L336), [341](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L341-L341), [345](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/PoolManager.sol#L345-L345)

```solidity
File: src/Root.sol

43:      function file(bytes32 what, uint256 data) external auth {

54:      function pause() external auth {

59:      function unpause() external auth {

65:      function scheduleRely(address target) external auth {

70:      function cancelRely(address target) external auth {

75:      function executeScheduledRely(address target) public {

90:      function relyContract(address target, address user) public auth {

98:      function denyContract(address target, address user) public auth {

```
*GitHub*: [43](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L43-L43), [54](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L54-L54), [59](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L59-L59), [65](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L65-L65), [70](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L70-L70), [75](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L75-L75), [90](https://github.com/code-423n4/2023-09-centrifuge/blob/0af232255c7d045efde4ac40801dfeeed8a8d889/src/Root.sol#L90-L90), [98](ht