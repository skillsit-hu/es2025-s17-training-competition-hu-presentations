# EuroSkills 2023 vs 2025 Web Development Competition - Module Comparison

This document provides a detailed comparison between the EuroSkills 2023 and EuroSkills 2025 Web Development competition module descriptions, highlighting substantial differences in structure, requirements, and assessment approaches.

## Competition Structure Overview

| Aspect | ES2023 | ES2025 |
|--------|--------|--------|
| **Total Duration** | 19 hours (6 modules) | 19 hours (6 modules) |
| **Competition Days** | C1, C2, C3 | C1 (Sep 10), C2 (Sep 11), C3 (Sep 12) |
| **Total Points** | 100 points | 100 points |
| **Module Names** | A-F (same basic structure) | A-F (same basic structure) |

---

## Module A - Static Website Design (HTML/CSS)

### Key Similarities
- **Duration**: 3 hours (both years)
- **Core Requirements**: Static HTML/CSS, multiple pages, responsive design, WCAG compliance, SEO best practices
- **Assessment**: W3C validation, axe accessibility testing, Chrome/Firefox testing
- **Restrictions**: No frameworks, CSS preprocessors allowed if W3C compliant

### **Substantial Differences**

#### Point Distribution
| WSOS Section | ES2023 Points | ES2025 Points | Change |
|--------------|---------------|---------------|---------|
| Work organization | 1 | 1.5 | +0.5 |
| Communication | 1 | 0 | -1 |
| Design Implementation | 15 | 15 | 0 |
| Front-End Development | 0 | 0 | 0 |
| Back-End Development | 0 | 0 | 0 |
| **Total** | **17** | **16.5** | **-0.5** |

#### Requirements Changes
- **ES2023**: Basic WCAG compliance mentioned
- **ES2025**: Specific requirement for "**WCAG level AA**" - more stringent accessibility standard
- **ES2025**: Enhanced emphasis on SEO for "product or service" vs general "product"

---

## Module B - Dynamic Website with Server-Side Rendering

### Key Similarities
- **Duration**: 4 hours (both years)
- **Core Requirements**: Server-side framework, protected areas, login system, OWASP guidelines, database design
- **Restrictions**: Server-side rendering mandatory (not client-side SPA calling API)

### **Substantial Differences**

#### Point Distribution
| WSOS Section | ES2023 Points | ES2025 Points | Change |
|--------------|---------------|---------------|---------|
| Work organization | 0 | 0 | 0 |
| Communication | 0 | 0 | 0 |
| Design Implementation | 5 | 4.75 | -0.25 |
| Front-End Development | 0 | 0 | 0 |
| Back-End Development | 18 | 18.25 | +0.25 |
| **Total** | **23** | **23** | **0** |

#### Requirements Changes
- **ES2023**: Data provided "in the form of CSV files"
- **ES2025**: Data provided as "example data" (format not specified) - more flexible
- **ES2025**: Explicit mention that data "might not be normalized" - clearer expectation for data processing skills

---

## Module C - REST API Development

### **Major Conceptual Differences**

#### ES2023: "Commercial Open API"
- **Complex Architecture**: API wraps multiple backend services with their own APIs
- **Service Integration**: Competitors wrap existing services rather than build from scratch
- **OpenAPI Specification**: Both input services and target API have detailed OpenAPI specs
- **Commercial Focus**: API designed for commercial, public access with security/reliability requirements
- **Dependency**: Uses Module B solution as foundation

#### ES2025: "REST API"
- **Direct Implementation**: Competitors build REST API from scratch
- **Database-Backed**: Direct database integration without service wrapping
- **External API Integration**: Fetches from external APIs (simpler integration model)
- **Clean Frontend-Ready API**: Focused on serving frontend applications
- **Role-Based Access**: Public endpoints + protected endpoints with role-based control

### Point Distribution
| WSOS Section | ES2023 Points | ES2025 Points | Change |
|--------------|---------------|---------------|---------|
| Work organization | 1 | 1 | 0 |
| Communication | 1 | 0.75 | -0.25 |
| Design Implementation | 0 | 0 | 0 |
| Front-End Development | 0 | 0 | 0 |
| Back-End Development | 15 | 15 | 0 |
| **Total** | **17** | **16.75** | **-0.25** |

### **Assessment Changes**
- **ES2023**: Cannot modify previous module solutions
- **ES2025**: Same restriction maintained

---

## Module D - Interactive Frontend using an API

### Key Similarities
- **Duration**: 4 hours (both years)
- **Core Requirements**: SPA frontend, uses Module C API, authentication, Chrome testing
- **Dependency**: Must use provided Module C solution

### **Substantial Differences**

#### Point Distribution
| WSOS Section | ES2023 Points | ES2025 Points | Change |
|--------------|---------------|---------------|---------|
| Work organization | 0 | 0 | 0 |
| Communication | 0 | 0 | 0 |
| Design Implementation | 5 | 5 | 0 |
| Front-End Development | 17 | 17 | 0 |
| Back-End Development | 0 | 0 | 0 |
| **Total** | **22** | **22** | **0** |

#### Functional Requirements
- **ES2023**: 
  - Complex API function discovery
  - Custom interactive elements per function
  - Asynchronous data handling
  - Comprehensive error handling
  - axe accessibility testing

- **ES2025**: 
  - API consumption and page display based on responses
  - User interaction � API actions
  - **Data polling** (new requirement)
  - **Data visualization** in different formats (new requirement)
  - **Third-party script integration** (new requirement)
  - No specific mention of accessibility testing

---

## Module E - Advanced Web Development

### **Major Content Differences**

#### ES2023: Three Distinct Tasks
1. **Writing automated tests** (JavaScript project, 100% coverage, mutation testing)
2. **Creating a Progressive Web App** (offline, push notifications, installable)
3. **Creating Web Components** (custom elements, specification-based)

#### ES2025: Three Different Tasks
1. **Writing automated tests** (same concept but refined process)
2. **OWASP Top 10 Security Vulnerabilities** (find and document security issues)
3. **Visual Appearance Preferences** (theme switching, CSS variables, user preferences)

### Point Distribution
| WSOS Section | ES2023 Points | ES2025 Points | Change |
|--------------|---------------|---------------|---------|
| Work organization | 2 | 0.5 | -1.5 |
| Communication | 1 | 3.5 | +2.5 |
| Design Implementation | 0 | 0 | 0 |
| Front-End Development | 8 | 5.75 | -2.25 |
| Back-End Development | 5 | 7 | +2 |
| **Total** | **16** | **16.75** | **+0.75** |

### **Assessment Approach Changes**
- **ES2023**: Focus on PWA and Web Components (modern web standards)
- **ES2025**: Focus on Security and UX (practical industry skills)
- **ES2025**: Explicit requirement for **Pull Request submissions** for tests
- **ES2025**: **Issue tracker documentation** for security findings

---

## Module F - Collaborative Challenge

### Key Similarities
- **Duration**: 2 hours (both years)
- **Core Concept**: Collaboration, creativity, presentation

### **Substantial Differences**

#### Point Distribution
| WSOS Section | ES2023 Points | ES2025 Points | Change |
|--------------|---------------|---------------|---------|
| Work organization | 1 | 2 | +1 |
| Communication | 2 | 1 | -1 |
| Design Implementation | 0 | 0 | 0 |
| Front-End Development | 0 | 2 | +2 |
| Back-End Development | 2 | 0 | -2 |
| **Total** | **5** | **5** | **0** |

#### Project Scope
- **ES2023**: 
  - Individual creativity within system integration
  - Must create API-compatible function
  - Integration with overall system architecture
  - More technical implementation focus

- **ES2025**: 
  - **Group collaboration** explicitly mentioned
  - Create "small web experience" 
  - Less emphasis on system integration
  - More emphasis on teamwork and presentation skills

---

## Summary of Major Changes

### 1. **Module C - Complete Redesign**
- **ES2023**: Complex service-wrapping commercial API
- **ES2025**: Direct database-backed REST API with external integration

### 2. **Module E - Content Overhaul**
- **ES2023**: PWA + Web Components (emerging web technologies)
- **ES2025**: Security + UX Preferences (practical development skills)

### 3. **Assessment Evolution**
- **ES2025**: More specific WCAG Level AA requirements
- **ES2025**: Pull Request workflows for test submissions
- **ES2025**: Issue tracker usage for security documentation
- **ES2025**: Enhanced group collaboration emphasis

### 4. **Technical Focus Shift**
- **ES2023**: Cutting-edge web technologies (PWA, Web Components, service architectures)
- **ES2025**: Industry-practical skills (security auditing, theming, direct API development)

### 5. **Point Redistribution**
- **Communication skills** points shifted from individual modules to Module E
- **Work organization** points increased in Module F (collaboration focus)
- **Front-end/Back-end balance** adjusted across modules

The 2025 competition appears to prioritize practical, industry-ready skills and collaborative workflows over cutting-edge web technologies, while maintaining the same overall structure and difficulty level.