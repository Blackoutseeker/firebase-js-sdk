## API Report File for "@firebase/functions-types-exp"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { FirebaseApp } from '@firebase/app-types-exp';
import { FirebaseError } from '@firebase/util';

// @public
export interface Functions {
  app: FirebaseApp;

  customDomain: string | null;

  region: string;
}

// @public (undocumented)
export interface FunctionsError extends FirebaseError {
  readonly code: FunctionsErrorCode;

  readonly details?: any;
}

// @public
export type FunctionsErrorCode =
  | 'ok'
  | 'cancelled'
  | 'unknown'
  | 'invalid-argument'
  | 'deadline-exceeded'
  | 'not-found'
  | 'already-exists'
  | 'permission-denied'
  | 'resource-exhausted'
  | 'failed-precondition'
  | 'aborted'
  | 'out-of-range'
  | 'unimplemented'
  | 'internal'
  | 'unavailable'
  | 'data-loss'
  | 'unauthenticated';

// @public
export interface HttpsCallable {
  // (undocumented)
  (data?: {} | null): Promise<HttpsCallableResult>;
}

// @public
export interface HttpsCallableOptions {
  // (undocumented)
  timeout?: number; // in millis
}

// @public
export interface HttpsCallableResult {
  // (undocumented)
  readonly data: any;
}


// (No @packageDocumentation comment for this package)

```
