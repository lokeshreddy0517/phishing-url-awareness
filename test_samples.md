# Test Results

Python version: 3.14.6
Operating system: Windows 11

| # | Sample URL | Expected warning | Result |
|---|---|---|---|
| 1 | https://www.example.com/login | No listed warning signs | PASS |
| 2 | http://192.0.2.10/account | IP address + HTTP | PASS |
| 3 | http://example.com@sample.invalid/login | @ symbol + HTTP | PASS |
| 4 | https://a.b.c.d.e.example.invalid/path | Many hostname segments | PASS |
| 5 | https://xn--example.invalid/ | Punycode-style hostname | PASS |

## Notes
- The program checks URL text only.
- It does not open websites.
- No warnings does not guarantee safety.