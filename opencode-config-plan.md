# OpenCode Configuration Planning Guide

## Current State Analysis
- Your current `opencode.jsonc` only has: `$schema` and `autoupdate: true`
- Missing `opencode.json` (project-level config)
- We'll enhance the existing file and potentially create the project one

## Proposed Workflow - Section by Section

For each section from the documentation, I'll:

1. **Show you the configuration properties** for that section
2. **Explain what each property does** in simple terms
3. **Ask if you want to include/enable** that feature
4. **Add appropriate annotations** explaining the choices

## Sections to Cover (in order):**

**Core Settings:**
1. **TUI** - Terminal UI behavior (`scroll_speed`, `scroll_acceleration`, `diff_style`)
2. **Server** - Server configuration (`port`, `hostname`, `mdns`, `cors`)
3. **Tools** - Tool permissions (`write`, `bash`, etc.)
4. **Models** - AI model configuration (`provider`, `model`, `small_model`)
5. **Themes** - Visual theme (`theme`)
6. **Agents** - Specialized agents configuration
7. **Default Agent** - Which agent to use by default
8. **Sharing** - Conversation sharing settings

**Advanced Settings:**
9. **Commands** - Custom commands
10. **Keybinds** - Custom keyboard shortcuts
11. **Formatters** - Code formatting
12. **Permissions** - Tool approval requirements
13. **Compaction** - Context management
14. **Watcher** - File watching patterns
15. **MCP Servers** - Model Context Protocol servers
16. **Plugins** - External plugins
17. **Instructions** - Custom instruction files
18. **Providers** - Provider enable/disable settings
19. **Experimental** - Experimental features

**Variables:**
20. **Environment Variables & Files** - Variable substitution

## Questions for You:

1. **Approach**: Do you want me to go through all sections systematically, or would you prefer to focus on specific sections first?

2. **Configuration Style**: Do you prefer:
   - Minimal configuration (only what you explicitly need)
   - Comprehensive with reasonable defaults
   - Educational with comments explaining everything

3. **Files**: Should I:
   - Enhance the existing `opencode.jsonc` 
   - Create both global (`opencode.jsonc`) and project (`opencode.json`) files
   - Just focus on the global config for now

4. **Priority**: Are there any specific sections you're most interested in configuring first?

Once you confirm your preferences, I'll start with the first section and show you all the available properties for that section before we proceed to add them to your configuration.

## Topic: OpenCode Configuration Section-by-Section Plan
Perfect! I now have the complete opencode configuration documentation. Let me create a comprehensive plan for going through this section by section and creating an annotated configuration file.

## **Plan: Section-by-Section OpenCode Configuration Annotation**

### **Current State Analysis**
- Your current `opencode.jsonc` only has: `$schema` and `autoupdate: true`
- Missing `opencode.json` (project-level config)
- We'll enhance the existing file and potentially create the project one

### **Proposed Workflow - Section by Section**

For each section from the documentation, I'll:

1. **Show you the configuration properties** for that section
2. **Explain what each property does** in simple terms
3. **Ask if you want to include/enable** that feature
4. **Add appropriate annotations** explaining the choices

### **Sections to Cover (in order):**

**Core Settings:**
1. **TUI** - Terminal UI behavior (`scroll_speed`, `scroll_acceleration`, `diff_style`)
2. **Server** - Server configuration (`port`, `hostname`, `mdns`, `cors`)
3. **Tools** - Tool permissions (`write`, `bash`, etc.)
4. **Models** - AI model configuration (`provider`, `model`, `small_model`)
5. **Themes** - Visual theme (`theme`)
6. **Agents** - Specialized agents configuration
7. **Default Agent** - Which agent to use by default
8. **Sharing** - Conversation sharing settings

**Advanced Settings:**
9. **Commands** - Custom commands
10. **Keybinds** - Custom keyboard shortcuts
11. **Formatters** - Code formatting
12. **Permissions** - Tool approval requirements
13. **Compaction** - Context management
14. **Watcher** - File watching patterns
15. **MCP Servers** - Model Context Protocol servers
16. **Plugins** - External plugins
17. **Instructions** - Custom instruction files
18. **Providers** - Provider enable/disable settings
19. **Experimental** - Experimental features

**Variables:**
20. **Environment Variables & Files** - Variable substitution

### **Questions for You:**

1. **Approach**: Do you want me to go through all sections systematically, or would you prefer to focus on specific sections first?

2. **Configuration Style**: Do you prefer:
   - Minimal configuration (only what you explicitly need)
   - Comprehensive with reasonable defaults
   - Educational with comments explaining everything

3. **Files**: Should I:
   - Enhance the existing `opencode.jsonc` 
   - Create both global (`opencode.jsonc`) and project (`opencode.json`) files
   - Just focus on the global config for now

4. **Priority**: Are there any specific sections you're most interested in configuring first?

Once you confirm your preferences, I'll start with the first section and show you all the available properties for that section before we proceed to add them to your configuration.

## Topic: Enhanced Plan with Message Logging Feature
I understand you want an enhanced plan that includes the ability to save any previous message on demand, using level two headers with brief descriptions.

## **Enhanced Plan: OpenCode Configuration Guide + Message Logging**

**When we exit plan mode, I will:**

### **1. Create the Configuration Planning Document**
**File**: `opencode-config-plan.md`

**Structure**:
```markdown
# OpenCode Configuration Planning Guide

## Current State Analysis
[Analysis of your current opencode.jsonc setup]

## Proposed Workflow - Section by Section
[Systematic approach through all 20 configuration sections]

## Configuration Sections to Cover
[List of all 20 sections with brief descriptions]

## Questions for Customization
[Your preferences for approach, style, files, and priority]

## Message Log
[Dynamic section for saving previous messages on demand]
```

### **2. Message Logging Feature**
**Enhanced capability**:
- **On-demand saving**: When you say "save the previous message," I'll:
  1. **Identify the last message** I sent
  2. **Create a level 2 header** with brief description
  3. **Append the content** to the `## Message Log` section
  4. **Use timestamped subsections** for organization

**Example format**:
```markdown
## Message Log

### OpenCode Configuration Section-by-Section Plan
*Date: Current timestamp*
[Full content of my previous detailed plan message]

### [Next Message Title]
*Date: Current timestamp*
[Content of whatever message you want to save]
```

### **3. Update Workflow**
**Whenever you request to save a message**:
1. **Read the current** `opencode-config-plan.md` file
2. **Identify your last request** (the previous message I sent)
3. **Create appropriate header** based on message content
4. **Append to Message Log section** with timestamp
5. **Save the updated file**

### **4. Header Guidelines**
**Level 2 headers (`##`)** will include:
- **Brief description** of the message content
- **Context** (what we were discussing)
- **Purpose** (why it's being saved)

**Examples**:
- `## OpenCode Configuration Section-by-Section Plan`
- `## Enhanced Plan with Message Logging Feature`
- `## Analysis of Current Configuration State`

### **5. File Management Rules**
- **Location**: Fixed as `opencode-config-plan.md` (using my suggested location)
- **Preservation**: Never delete without explicit permission
- **Updates**: Immediate execution upon request
- **Organization**: Separate sections for each distinct topic

## Topic: Final Enhanced Plan with Message Logging Preferences
Perfect! I have your preferences clearly defined. Here's the final enhanced plan:

## **Final Enhanced Plan: OpenCode Configuration Guide with Message Logging**

### **1. Initial Document Creation**
**File**: `opencode-config-plan.md` (using my suggested location)

**Document Structure**:
```markdown
# OpenCode Configuration Planning Guide

## Current State Analysis
[Analysis of your current setup]

## Proposed Workflow - Section by Section
[Systematic approach through all sections]

## Configuration Sections to Cover
[Complete list of 20 sections]

## Questions for Customization
[Your preferences for implementation]

## Topic: OpenCode Configuration Planning
*Initial comprehensive planning message*

## Topic: [Next Topic Name]
[Future messages as requested]
```

### **2. Message Logging Protocol**
**When you request "save the previous message":**

1. **Immediate save** - No confirmation needed
2. **Never delete** - Preserve all content unless explicitly instructed
3. **Separate sections** - Each topic gets its own `## Topic: [Name]` section
4. **Brief descriptive names** - Based on message content
5. **Chronological order** - New topics appended at the end

### **3. Topic Section Format**
```markdown
## Topic: [Descriptive Title]
*Content of the message being saved*
```

### **4. File Management Rules**
- **Location**: Fixed as `opencode-config-plan.md` 
- **Preservation**: Never delete without explicit permission
- **Updates**: Immediate execution upon request
- **Organization**: Separate sections for each distinct topic

### **5. Ready for Execution**
**When you exit plan mode, I will:**
1. Create the initial `opencode-config-plan.md` file
2. Include all current planning content organized into topic sections
3. Be ready to save any future messages immediately upon request
4. Maintain the document as a living record of our planning process

**All preferences confirmed**:
✅ File location: `opencode-config-plan.md`  
✅ Separate sections for each topic  
✅ No specific header format required  
✅ Immediate save on request  
✅ Never delete without explicit permission  

This plan is now ready for execution. Just let me know when you'd like to exit plan mode and I'll create the initial document with all our current planning content organized into topic sections.

## Topic: Tools Configuration Section
## **Section 3: Tools Configuration**

Here are all the available tools properties with their default values:

```json
{
  "tools": {
    "write": true,      // Allow file writing operations (default: true)
    "bash": true,       // Allow bash command execution (default: true)
    "read": true,       // Allow file reading operations (default: true)
    "edit": true,       // Allow file editing operations (default: true)
    "glob": true,       // Allow file pattern matching (default: true)
    "grep": true,       // Allow content searching (default: true)
    "webfetch": true,   // Allow web content fetching (default: true)
    "websearch": true,  // Allow web searching (default: true)
    "codesearch": true, // Allow code documentation search (default: true)
    "task": true,       // Allow agent task delegation (default: true)
    "todowrite": true,  // Allow todo list creation (default: true)
    "todoread": true,   // Allow todo list reading (default: true)
    "question": true,   // Allow user questioning (default: true)
    "skill": true,      // Allow skill loading (default: true)
    // Additional tool-specific options may exist
  }
}
```

**Property Details:**
- **write**: Create/overwrite files
- **bash**: Execute terminal commands
- **read**: Read file contents
- **edit**: Make precise file edits
- **glob**: Pattern-based file discovery
- **grep**: Content-based file searching
- **webfetch**: Retrieve web pages
- **websearch**: Search the internet
- **codesearch**: Search programming documentation
- **task**: Launch specialized agents
- **todowrite/todoread**: Manage task lists
- **question**: Prompt users for input
- **skill**: Load specialized capabilities

**Usage Examples:**
```json
// Disable dangerous tools
"tools": {
  "write": false,    // Prevent file creation
  "bash": false      // Prevent command execution
}

// Enable read-only mode
"tools": {
  "write": false,
  "edit": false,
  "bash": false,
  // ... keep read-only tools enabled
}
```

Ready for the next section when you want to continue!
```

## Topic: Commands Configuration Section
## **Section 9: Commands Configuration**

Here are all the available commands properties with their default values:

```json
{
  "command": {}  // Custom command definitions object (default: empty object)
}
```

**Command Structure:**
```json
{
  "command": {
    "command-name": {
      "template": "Command template with $ARGUMENTS placeholder",  // Required
      "description": "Brief description of what the command does",   // Default: undefined
      "agent": "agent-name",                                    // Default: undefined (uses default agent)
      "model": "anthropic/claude-sonnet-4-5"                   // Default: undefined (uses default model)
    }
  }
}
```

**Property Details:**
- **template**: Command text template with `$ARGUMENTS` placeholder (required)
- **description**: What command does (optional)
- **agent**: Which agent to use for this command (optional)
- **model**: Which model to use for this command (optional)

**Example:**
```json
{
  "command": {
    "test": {
      "template": "Run the full test suite with coverage report and show any failures.\nFocus on the failing tests and suggest fixes.",
      "description": "Run tests with coverage",
      "agent": "build",
      "model": "anthropic/claude-haiku-4-5"
    },
    "component": {
      "template": "Create a new React component named $ARGUMENTS with TypeScript support.\nInclude proper typing and basic structure.",
      "description": "Create a new component"
    }
  }
}
```

Ready for the next section when you want to continue!
```