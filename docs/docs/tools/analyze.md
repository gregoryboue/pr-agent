## Overview
The `analyze` tool combines static code analysis with LLM capabilities to provide a comprehensive analysis of the PR code changes.

The tool scans the PR code changes, find the code components (methods, functions, classes) that changed, and summarizes the changes in each component.

It can be invoked manually by commenting on any PR:
```
/analyze
```

## Example usage
An example [result](https://github.com/Codium-ai/pr-agent/pull/546#issuecomment-1868524805):

![Analyze 1](https://codium.ai/images/pr_agent/analyze_1.png){width=750}
&rarr;
![Analyze 2](https://codium.ai/images/pr_agent/analyze_2.png){width=750}
&rarr;
![Analyze 3](https://codium.ai/images/pr_agent/analyze_3.png){width=750}

**Notes**

- Language that are currently supported: Python, Java, C++, JavaScript, TypeScript, C#.