# RecIT - Ultimate Recon Script 💥

## What is RecIT?

RecIT is a comprehensive reconnaissance automation script developed by 0xParth that streamlines the entire reconnaissance process for security professionals, bug bounty hunters, and CEH practitioners. The tool integrates 18 different security tools into a single, powerful workflow that automates subdomain enumeration, vulnerability scanning, parameter discovery, and more.

## How RecIT Can Help CEH Learners

### 1. **Automated Reconnaissance Workflow**
- Saves hours of manual work by automating the entire recon process
- Reduces the chance of missing important targets or vulnerabilities
- Allows learners to focus on analysis rather than data collection

### 2. **Integration of Industry-Standard Tools**
RecIT seamlessly integrates the following tools that are essential for CEH practitioners:

1. **Subfinder** - Fast passive subdomain enumeration tool
2. **Amass** - In-depth attack surface mapping and asset discovery
3. **Assetfinder** - Find domains and subdomains related to a given domain
4. **Github Subdomains** - Extract subdomains from GitHub search results
5. **Sub Scraper** - Subdomain enumeration through various techniques
6. **Httpx** - Fast and multi-purpose HTTP toolkit
7. **Httprobe** - Probe for working HTTP and HTTPS servers
8. **Nuclei** - Template-based vulnerability scanner
9. **Naabu** - Fast port scanner written in Go
10. **Gauplus** - Fetch URLs from multiple sources
11. **Anew** - Tool for adding new lines to files, skipping duplicates
12. **ParamSpider** - Mining parameters from dark corners of web archives
13. **Dalfox** - XSS scanner and parameter analysis tool
14. **Git Dorker** - Scan GitHub for sensitive information
15. **Ffuf** - Fast web fuzzer for directory/file discovery
16. **Arjun** - HTTP parameter discovery suite
17. **Gf** - Grep for URLs with custom patterns
18. **Gf-Patterns** - Custom patterns for finding sensitive information

### 3. **Practical Benefits for CEH Exam**
- **Real-world Application**: The script demonstrates how tools work together in actual penetration testing scenarios
- **Time Management**: During practical exams, time is crucial. Understanding automated workflows helps optimize your approach
- **Comprehensive Coverage**: Ensures no critical reconnaissance step is missed
- **Pattern Recognition**: Helps identify common vulnerabilities and attack vectors

## Technical Implementation

### Core Functionality
RecIT performs the following key operations:
1. **Subdomain Enumeration**: Collects subdomains from multiple sources
2. **Live Host Detection**: Identifies which discovered hosts are actually reachable
3. **Port Scanning**: Discovers open ports on live hosts
4. **URL Collection**: Gathers URLs from various sources including web archives
5. **Parameter Discovery**: Identifies potential injection points
6. **Vulnerability Scanning**: Runs automated scans for common vulnerabilities
7. **XSS Testing**: Specifically tests for cross-site scripting vulnerabilities
8. **Sensitive Data Discovery**: Searches for exposed sensitive information

### Usage Workflow
1. Input a target domain
2. RecIT automatically runs through all integrated tools
3. Results are organized and saved for analysis
4. Security professionals can then focus on manual verification and exploitation

## Last Update Information

**Last Commit Date**: June 27, 2022  
**Last Commit Message**: "Updated One Liner"  
**Commit Author**: parthshu18 (shukla.pa@northeastern.edu)

### What Changed in the Last Update
The last update focused on improving the one-liner commands within the script, likely making the tool more efficient and easier to use. This demonstrates the continuous improvement approach that security professionals should adopt.

## How to Use RecIT for CEH Preparation

### 1. **Installation**
- Clone the RecIT repository
- Install all 18 required tools listed above
- Ensure all tools are in your system PATH

### 2. **Practice Scenarios**
- Use RecIT on legal practice targets (VulnHub, HackTheBox, etc.)
- Analyze the output from each tool to understand what it discovers
- Cross-reference findings with manual testing

### 3. **Learning Objectives**
- Understand how each tool contributes to the reconnaissance phase
- Learn to interpret and correlate results from multiple tools
- Develop skills in identifying false positives
- Practice prioritizing findings based on severity

## Best Practices for CEH Learners

1. **Don't Just Run - Understand**: While RecIT automates the process, make sure you understand what each tool does
2. **Manual Verification**: Always verify automated findings manually
3. **Legal Considerations**: Only use on authorized targets
4. **Documentation**: Keep detailed notes on findings and methodologies
5. **Continuous Learning**: Stay updated with new tools and techniques

## Integration with CEH Practical Exam

RecIT demonstrates several key concepts tested in the CEH practical exam:
- Reconnaissance and footprinting
- Scanning and enumeration
- Vulnerability assessment
- Understanding of multiple security tools
- Automation and scripting capabilities

## Conclusion

RecIT is more than just a tool - it's a comprehensive framework that demonstrates how modern penetration testers approach reconnaissance. For CEH learners, understanding and using RecIT provides insights into:
- Professional workflows
- Tool integration
- Automation benefits
- Comprehensive security testing

By mastering RecIT and understanding its components, CEH candidates will be better prepared for both the practical exam and real-world security assessments.

---

**Note**: Always ensure you have proper authorization before running RecIT or any reconnaissance tools against a target. Unauthorized scanning is illegal and unethical.