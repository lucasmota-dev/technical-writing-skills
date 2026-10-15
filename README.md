# Technical Writing Skills

Skills for AI assistants that help create and review technical documentation in clear, consistent language, in English and Brazilian Portuguese.

The goal is to make procedures, user instructions, descriptions, requirements, and support content easier to understand without changing technical meaning or inventing behavior.

## Available skills

### ASD-STE100 — Simplified Technical English

**Path:** `asd-ste100-english/SKILL.md`

A practical writing skill based on **ASD-STE100 Issue 9 (15 January 2025)**. It uses the standard's organization and rule summaries to guide controlled vocabulary, approved meanings and parts of speech, verb forms, multi-word nouns, procedure writing, descriptive writing, safety instructions, punctuation, word counting, and consistent writing practices.

For strict STE work, use the official standard and dictionary as the source of truth:

- [ASD-STE100 official website](https://www.asd-ste100.org/)
- [Official standard and dictionary access](https://www.asd-ste100.org/STE_downloads.html)

This skill is a practical summary. It does not reproduce the complete standard or dictionary. It cannot certify compliance unless the applicable rules and dictionary entries have been checked.

### Brazilian Portuguese — Controlled Technical Language

**Path:** `pt-br-controlled-language/SKILL.md`

An adaptation of transferable technical-writing principles for Brazilian Portuguese. It supports user instructions, software documentation, requirements, acceptance criteria, interface messages, tickets, and technical communication.

The Portuguese skill is **not an official translation of ASD-STE100**. In this repository, *Português Técnico Controlado (PTC)* is a proposed editorial convention, not a published standard. English-specific constraints—such as rules for verb forms, the three-word limit for noun groups, the prohibition on semicolons, and the English word-count limits—must not be applied automatically to Portuguese.

## Principles covered

- Use clear, direct language suited to the reader and task.
- Keep terminology consistent and preserve official product and interface names.
- Make actions, conditions, prerequisites, results, and exceptions explicit.
- Separate procedural instructions from descriptive explanations.
- Preserve technical facts, limits, warnings, and requirements.
- Avoid unsupported assumptions about causes or system behavior.
- Review safety content against the applicable requirements.

The English skill additionally summarizes relevant Issue 9 controls, including its requirements for vocabulary selection, approved meanings and forms, sentence construction, procedure and description word limits, paragraph structure, punctuation, and word-count conventions.

## Example

**Before**

> Para que seja possível efetuar a alteração desejada, deverá ser realizada a seleção do registro correspondente e, posteriormente, deverá ser acionado o recurso de gravação.

**After**

> Abra o cadastro. Selecione o registro que deseja alterar. Edite os campos necessários e clique em **Salvar**.

Use the exact labels shown by the actual system in production documentation.

## How to use

1. Choose the skill for the language of the content.
2. Copy the relevant folder to the skills or instruction location supported by your AI tool.
3. Enable or configure the skill as required by that tool.
4. Ask the assistant to write, rewrite, simplify, or review the content using the selected skill.

The installation method depends on the AI tool. A `SKILL.md` file does not by itself guarantee automatic compatibility with every assistant.

## Review and accuracy

The skills support writing and review; they do not replace technical validation by a subject-matter expert. Check all facts, requirements, operational procedures, and safety information before publication or use.

For English STE, do not claim verified compliance without checking the official Issue 9 writing rules and dictionary. For Brazilian Portuguese, use the skill as an editorial guide and follow the grammar, legal requirements, and technical conventions that apply to the project.

## Contributing

Suggestions and contributions are welcome. Describe the problem a change solves and, where possible, include a before-and-after example. Keep the official English standard distinct from the Portuguese adaptation.

## Reference

ASD-STE100, *Simplified Technical English — Standard for technical documentation*, Issue 9, 15 January 2025. Copyright and trademark belong to ASD. This repository contains original practical guidance based on the standard's principles; it does not include the source PDF or reproduce the full standard or dictionary.

- [Official website](https://www.asd-ste100.org/)
- [Official download page](https://www.asd-ste100.org/STE_downloads.html)

---

## English summary

This repository provides two AI writing skills for clearer technical communication:

- **`asd-ste100-english/`** — a practical summary based on ASD-STE100 Issue 9. It does not replace the official standard or dictionary and does not guarantee compliance.
- **`pt-br-controlled-language/`** — an adaptation of controlled technical-writing principles for Brazilian Portuguese. It is not an official Portuguese version of ASD-STE100.

The skills support technical documentation, user instructions, procedures, software requirements, interface messages, and support content. Review generated content for technical accuracy before publication or operational use.
