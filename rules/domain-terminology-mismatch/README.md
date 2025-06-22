# Domain Terminology Mismatch Rules

The purpose of this kind of rules file is to make your coding assistant aware of mismatches in your domain terminology - where the concepts in your code no longer align with the current business terminology. This enalbes your assistant to prefer the correct terminology and even propose refactoring opportunities to move your codebase towards your target model.

For this file, I experimented using XML to provide the information in a more structured manner. But XML is not necessary and it doesn't even need to be valid XML. The LLM is going to read it. You might get similar or better results just using simple plan text.

## Tips

1. You can combine this rules files with others like refactoring. E.g. Ask your refactoring rules/prompts to use these terminology rules to identify refactoring opportunities in an area of the codebase (or the whole codebase)