# AutoHotkey v2 XML Reference Documentation

This document provides an overview of AutoHotkey v2's XML-based documentation structure, designed to serve as comprehensive context for AI code generation and IDE tooling. These XML files contain the fundamental knowledge needed to understand and generate valid AutoHotkey v2 code.

## Core Language Files

### 1. Directives.xml
Defines valid script-level directives and their usage:
- Syntax patterns for directives (#Include, #HotIf, #SingleInstance)
- Parameter requirements and constraints
- Usage context and limitations

### 2. Classes.xml
Documents the object-oriented foundation of AHK v2:
- Complete class hierarchy and inheritance patterns
- Built-in class definitions and methods
- Method signatures with parameter types and return values

### 3. Functions.xml
Catalogs all built-in functions with their specifications:
- Function signatures and calling patterns
- Parameter types and validation rules
- Return value specifications
- Usage contexts and common patterns

### 4. Operators.xml
Specifies operator behavior and syntax:
- Valid operator combinations and precedence
- Type handling and coercion rules
- Assignment and comparison patterns
- Special operator usage (., ??, ?:)

### 5. FlowControls.xml
Details control structure implementation:
- Loop construction and valid syntax
- Conditional statement patterns
- Error handling implementation
- Flow control keywords and usage

## Template and Pattern Files

### 6. GuiTemplates.xml
Standard patterns for GUI implementation:
- Window creation and management
- Control layout and interaction
- Event binding patterns

### 7. ErrorHandling.xml
Error management patterns:
- Exception handling structures
- Error class implementations
- Common error scenarios and handling

### 8. EventHandling.xml
Event system implementation patterns:
- Hotkey and hotstring handling
- Window and system event management
- Input processing patterns

## Usage for AI and IDE Integration

These XML files are structured to provide:
1. Syntax validation rules for code generation
2. Type checking and parameter validation
3. Context-aware code completion
4. Pattern recognition for common implementations

## File Organization

The documentation is organized to facilitate:
1. Code generation and validation
2. Context-aware suggestions
3. Pattern matching and implementation guidance

This structure enables AI systems and IDEs to generate and validate AutoHotkey v2 code with high accuracy and adherence to best practices.
